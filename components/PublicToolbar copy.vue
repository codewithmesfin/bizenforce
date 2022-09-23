<template>
  <div>
      <div class="hidden md:block max-w-[100%] border mx-auto px-2 sm:px-6 lg:px-8">
          <div class="relative flex items-center justify-between h-16">

              <div
                  class="flex justify-between md:justify-around py-4 bg-white/80 border backdrop-blur-md  px-10 fixed top-0 left-0 right-0 z-10 px-8 md:px-3">
                  <div class="flex-shrink-0 flex items-center">
                      <img class="block lg:hidden h-8 w-auto"
                          src="https://stackoverflow.design/assets/img/logos/so/logo-stackoverflow.svg"
                          alt="Workflow" />
                      <img class="hidden lg:block h-8 w-auto"
                          src="https://stackoverflow.design/assets/img/logos/so/logo-stackoverflow.svg"
                          alt="Workflow" />
                  </div>

                  <div class="hidden  sm:block sm:ml-6">

                      <div
                          class="items-center md:space-x-8 justify-center justify-items-start md:justify-items-center md:flex md:pt-2 w-full left-0 top-16 px-5 md:px-10 py-3 md:py-0 border-t md:border-t-0">
                          <span v-for="(nav,i) in navigations" :key="i">
                              <NuxtLink to="sfd"
                                  :class="nav.current? 'flex text-gray-600 cursor-pointer transition-colors duration-300 font-semibold text-blue-600':'flex text-gray-600 hover:text-blue-500 cursor-pointer transition-colors duration-300'">
                                  {{nav.name}}
                              </NuxtLink>
                          </span>

                      </div>
                  </div>
                  <!-- Auth Links -->
                  <div class="flex items-center space-x-5 hidden md:flex">
                      <!-- Register -->
                      <a class="flex text-gray-600 hover:text-blue-500 cursor-pointer transition-colors duration-300">
                          <svg class="fill-current h-5 w-5 mr-2 mt-0.5" xmlns="http://www.w3.org/2000/svg"
                              xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" width="24" height="24"
                              viewBox="0 0 24 24">
                              <path
                                  d="M12 0L11.34 .03L15.15 3.84L16.5 2.5C19.75 4.07 22.09 7.24 22.45 11H23.95C23.44 4.84 18.29 0 12 0M12 4C10.07 4 8.5 5.57 8.5 7.5C8.5 9.43 10.07 11 12 11C13.93 11 15.5 9.43 15.5 7.5C15.5 5.57 13.93 4 12 4M12 6C12.83 6 13.5 6.67 13.5 7.5C13.5 8.33 12.83 9 12 9C11.17 9 10.5 8.33 10.5 7.5C10.5 6.67 11.17 6 12 6M.05 13C.56 19.16 5.71 24 12 24L12.66 23.97L8.85 20.16L7.5 21.5C4.25 19.94 1.91 16.76 1.55 13H.05M12 13C8.13 13 5 14.57 5 16.5V18H19V16.5C19 14.57 15.87 13 12 13M12 15C14.11 15 15.61 15.53 16.39 16H7.61C8.39 15.53 9.89 15 12 15Z" />
                          </svg>

                          Register
                      </a>

                      <!-- Login -->
                      <a
                          class="flex text-gray-600 cursor-pointer transition-colors duration-300 font-semibold text-blue-600">
                          <svg class="fill-current h-5 w-5 mr-2 mt-0.5" xmlns="http://www.w3.org/2000/svg"
                              xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" width="24" height="24"
                              viewBox="0 0 24 24">
                              <path
                                  d="M10,17V14H3V10H10V7L15,12L10,17M10,2H19A2,2 0 0,1 21,4V20A2,2 0 0,1 19,22H10A2,2 0 0,1 8,20V18H10V20H19V4H10V6H8V4A2,2 0 0,1 10,2Z" />
                          </svg>

                          Login
                      </a>
                  </div>

              </div>

          </div>
      </div>
      <div class="block md:hidden fixed top-0 left-0 right-0 z-10  bg-white overflow-hidden">
          <div class="max-w-[90%] mx-auto">
              <div class="
          relative
          z-10
          pb-8
          bg-white
          sm:pb-16
          md:pb-20
          lg:max-w-2xl lg:w-full lg:pb-28
          xl:pb-32
        ">
                  <svg class="
            hidden
            lg:block
            absolute
            right-0
            inset-y-0
            h-full
            w-48
            text-white
            transform
            translate-x-1/2
          " fill="currentColor" viewBox="0 0 100 100" preserveAspectRatio="none" aria-hidden="true">
                      <polygon points="50,0 100,0 50,100 0,100" />
                  </svg>

                  <Popover>
                      <div class="relative pt-6 px-4 sm:px-6 lg:px-8">
                          <nav class="
                relative
                flex
                items-center
                justify-between
                sm:h-10
                lg:justify-start
              " aria-label="Global">
                              <div class="
                  flex
                  items-center
                  flex-grow flex-shrink-0
                  lg:flex-grow-0
                ">
                                  <div class="flex items-center z-50 justify-between w-full md:w-auto">
                                      <a href="#">
                                          <span class="sr-only">Workflow</span>
                                          <img alt="Workflow" class="h-8 w-auto sm:h-10"
                                              src="https://tailwindui.com/img/logos/workflow-mark.svg?color=indigo&shade=600" />
                                      </a>
                                      <div class="-mr-2 flex items-center md:hidden">
                                          <PopoverButton class="
                        bg-white
                        rounded-md
                        p-2
                        inline-flex
                        items-center
                        justify-center
                        text-gray-400
                        hover:text-gray-500 hover:bg-gray-100
                        focus:outline-none
                        focus:ring-2
                        focus:ring-inset
                        focus:ring-indigo-500
                      ">
                                              <span class="sr-only">Open main menu</span>
                                              <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none"
                                                  viewBox="0 0 24 24" stroke-width="2" stroke="currentColor"
                                                  aria-hidden="true">
                                                  <path stroke-linecap="round" stroke-linejoin="round"
                                                      d="M4 6h16M4 12h16M4 18h16" />
                                              </svg>
                                          </PopoverButton>
                                      </div>
                                  </div>
                              </div>
                             
                          </nav>
                      </div>

                      <transition enter-active-class="duration-150 ease-out" enter-from-class="opacity-0 scale-95"
                          enter-to-class="opacity-100 scale-100" leave-active-class="duration-100 ease-in"
                          leave-from-class="opacity-100 scale-100" leave-to-class="opacity-0 scale-95">
                          <PopoverPanel focus class="
                absolute
                z-10
                top-0
                inset-x-0
                p-2
                transition
                transform
                origin-top-right
                md:hidden
              ">
                              <div class="
                  rounded-lg
                  shadow-md
                  bg-white
                  ring-1 ring-black ring-opacity-5
                  overflow-hidden
                ">
                                  <div class="px-5 pt-4 flex items-center justify-between">
                                      <div>
                                          <img class="h-8 w-auto"
                                              src="https://tailwindui.com/img/logos/workflow-mark.svg?color=indigo&shade=600"
                                              alt="" />
                                      </div>
                                      <div class="-mr-2">
                                          <PopoverButton class="
                        bg-white
                        rounded-md
                        p-2
                        inline-flex
                        items-center
                        justify-center
                        text-gray-400
                        hover:text-gray-500 hover:bg-gray-100
                        focus:outline-none
                        focus:ring-2
                        focus:ring-inset
                        focus:ring-indigo-500
                      ">
                                              <span class="sr-only">Close main menu</span>
                                              <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none"
                                                  viewBox="0 0 24 24" stroke-width="2" stroke="currentColor"
                                                  aria-hidden="true">
                                                  <path stroke-linecap="round" stroke-linejoin="round"
                                                      d="M6 18L18 6M6 6l12 12" />
                                              </svg>
                                          </PopoverButton>
                                      </div>
                                  </div>
                                  <div class="px-2 pt-2 pb-3 space-y-1">
                                      <a v-for="item in navigations" :key="item.name" :href="item.href" class="
                      block
                      px-3
                      py-2
                      rounded-md
                      text-base
                      font-medium
                      text-gray-700
                      hover:text-gray-900 hover:bg-gray-50
                    ">{{ item.name }}</a>
                                  </div>
                                  <a href="/auth/signin" class="
                    block
                    w-full
                    px-5
                    py-3
                    text-center
                    font-medium
                    text-indigo-600
                    bg-gray-50
                    hover:bg-gray-100
                  ">
                                      Log in
                                  </a>
                              </div>
                          </PopoverPanel>
                      </transition>
                  </Popover>

               
              </div>
          </div>
         
      </div>
  </div>

</template>


<script setup>
import { Popover, PopoverButton, PopoverPanel } from "@headlessui/vue";

const navigations = [
  { name: "Home", href: "", current: true },
  { name: "About", href: "about", current: false },
  { name: "Problems", href: "problems", current: false },
  { name: "Solutions", href: "solutions", current: false },
  { name: "Learn", href: "learn", current: false },
  { name: "Team", href: "team", current: false },
  { name: "Support", href: "support", current: false },
];
</script>