<template>
  <div>
    <div x-data="setup()" :class="{ dark: isDark }">
      <div
        class="
          min-h-screen
          flex flex-col flex-auto flex-shrink-0
          antialiased
          bg-white
          dark:bg-gray-700
          text-black
          dark:text-white
        "
      >
        <Toolbar />
        <Sidebar />
        <div class="h-full ml-14 mb-10 md:ml-64">
          <div class="m-4 p-5">
            <h1>Contents ...</h1>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Toolbar from "../../components/Toolbar.vue";
import Sidebar from "../../components/Sidebar.vue";
export default {
  components: { Sidebar, Toolbar },
};
</script>