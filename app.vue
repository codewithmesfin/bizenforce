
<template>
  <div>
    <NuxtPage />
    <FooterFooter />
  </div>
</template>

<script>
import FooterFooter from "./components/Footer.vue";
import Pricing from "./components/Pricing.vue";
export default {
  components: { Pricing, FooterFooter },
};
</script>
