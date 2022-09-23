
<template>
  <div class="mb-[30%]">
    <NuxtLayout />
    <PublicToolbarVue />
    <section>
      <div class="flex ml-auto max-w-[94%] pt-16">
        <main class="
              mx-auto
              max-w-[100%]
             xs:w-[100%]
             md:w-[50%]
              px-4
              sm:mt-12 sm:px-6
              md:mt-16
              lg:mt-20 lg:px-8
              xl:mt-28
            ">
          <div class="sm:text-center lg:text-left">
            <h1 class="
                  text-4xl
                  tracking-tight
                  font-bold
                  text-gray-900
                  sm:text-5xl sm:tracking-tight
                  md:text-6xl md:tracking-tight
                ">
              <span class="block xl:inline">Keep your project management </span>

              <span class="block text-blue-600 xl:inline"> simple and effective</span>
            </h1>
            <p class="
                  mt-3
                  text-base text-black
                  sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto
                  md:mt-5 md:text-xl
                  lg:mx-0
                ">
              Anim aute id magna aliqua ad ad non deserunt sunt. Qui irure qui
              lorem cupidatat commodo. Elit sunt amet fugiat veniam occaecat
              fugiat aliqua. <NuxtLink class="text-blue-600" to="/learn-more">Learn More ...</NuxtLink>
            </p>

          </div>
        </main>
        <div class="xs:w-[100%]
             md:w-[50%] lg:inset-y-0 lg:right-0 lg:w-1/2">
          <img class="h-56 md:w-full object-cover sm:h-72 md:h-96 lg:w-full lg:h-full"
            src="https://images.unsplash.com/photo-1551434678-e076c223a692?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2850&q=80"
            alt="" />
        </div>
      </div>
    </section>

    <!-- This example requires Tailwind CSS v2.0+ -->

    <section>
      <!-- This example requires Tailwind CSS v2.0+ -->

      <div class="bg-gray-50">
        <div class="mx-auto max-w-7xl py-12 px-4 sm:px-6 lg:flex lg:items-center lg:justify-between lg:py-16 lg:px-8">
          <div class="w-[40%]">
            <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">
              <span class="block">Ready to dive in?</span>
              <span class="block text-indigo-600 py-2">Try BizEnforce, it is 100% free.</span>
            </h2>
            <p> We are working hard to help you end up with a successfull project!</p>
            <div class="my-3 flex justify-between">
              <NuxtLink to="/sdfd" type="button"
                class="border  w-[100%] text-center  border-indigo-500 bg-indigo-500 text-white rounded-md px-4 py-2 m-2 transition duration-500 ease select-none hover:bg-indigo-600 focus:outline-none focus:shadow-outline">
                Get Started
              </NuxtLink>
              <NuxtLink to="/sdfd" type="button"
                class="border w-[100%] text-center shadow border-white bg-white text-blue-600 rounded-md px-4 py-2 m-2 transition duration-500 ease select-none focus:outline-none focus:shadow-outline">
                How it works ?
              </NuxtLink>
            </div>
          </div>
          <div class="mt-8 flex lg:mt-0 lg:flex-shrink-0 w-full md:max-w-[50%]">
            <div class="mx-2 w-[100%]">
              <img class="w-full h-[200px]"
                src="https://d2slcw3kip6qmk.cloudfront.net/marketing/blog/2019Q1/why-pm-is-important/why-is-project-management-important-header@2x.png"
                alt="">
              <NuxtLink to="/sdfd" type="button"
                class="border text-center  border-indigo-500 bg-indigo-500 text-white  px-4 py-2 mt-3 transition duration-500 ease select-none hover:bg-indigo-600 focus:outline-none focus:shadow-outline">
                Watch Demos
              </NuxtLink>
            </div>
            <div class="mx-2 w-[100%]">
              <img class="w-full  h-[200px]"
                src="https://www.everywoman.com/wp-content/uploads/2022/02/laughing-girl-showing-thumbs-up-picture-id505175324.jpg"
                alt="">
              <NuxtLink to="/sdfd" type="button"
                class="border text-center  border-indigo-500 bg-indigo-500 text-white  px-4 py-2 mt-3 transition duration-500 ease select-none hover:bg-indigo-600 focus:outline-none focus:shadow-outline">
                Success Stories
              </NuxtLink>
            </div>

          </div>
        </div>
      </div>
    </section>

    <section class="flex mx-auto max-w-[70%] pt-16">
      <div>
        <h2 class="block text-3xl text-left font-bold tracking-tight  sm:text-4xl text-black">
          Why BizEnforce ?
        </h2>
        <p>Our vision is to provide an excellent coffee product to customers and provide a real value to the world</p>

        <div class="flex">
          <div class="m-3 ml-0 md:w-[100%] min-w-[300px]">
            <img class="w-full min-w-[200px] h-[150px]"
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRF65NJuOHAN_r7uvxPRgLlU2rewOiN0dKtGsjP0NKggwKiy3oWnjIoIaNfHptypJ9bKrk&usqp=CAU"
              alt="">
          </div>
          <div class="m-3">
            <p>
              Fugiat ipsum ipsum deserunt culpa aute sint do nostrud anim incididunt cillum culpa consequat. Excepteur
              qui ipsum aliquip consequat sint. Sit id mollit nulla mollit nostrud in ea officia proident. Irure nostrud
              pariatur mollit ad adipisicing reprehenderit deserunt qui eu.
              Fugiat ipsum ipsum deserunt culpa aute sint do nostrud anim incididunt cillum culpa consequat. Excepteur
              qui ipsum aliquip consequat sint. Sit id mollit nulla mollit nostrud in ea officia proident. Irure nostrud
              pariatur mollit ad adipisicing reprehenderit deserunt qui eu.
            </p>
          </div>
        </div>
      </div>

    </section>

    <section>
      <div class="mx-auto max-w-7xl py-12 px-4 sm:px-6 lg:flex lg:items-center lg:justify-between lg:py-16 lg:px-8">
        <div class="flex">
          <div class="max-w-[600px] ">
            <img class="w-full max-w-[600px]  h-full "
              src="https://www.everywoman.com/wp-content/uploads/2022/02/laughing-girl-showing-thumbs-up-picture-id505175324.jpg"
              alt="">
            <h2 class="text-3xl py-2 font-bold tracking-tight text-gray-900 sm:text-4xl">
              <span class="block text-indigo-600">Workflow management</span>
            </h2>
            <p>
              Fugiat ipsum ipsum deserunt culpa aute sint do nostrud anim incididunt cillum culpa consequat. Excepteur
              qui ipsum aliquip consequat sint. Sit id mollit nulla mollit nostrud in ea officia proident. Irure nostrud
              pariatur mollit ad adipisicing reprehenderit deserunt qui eu.
            </p>
            <NuxtLink to="/sdfd" type="button"
              class="border text-center  border-indigo-500 bg-indigo-500 text-white rounded-md px-4 py-2 m-2 transition duration-500 ease select-none hover:bg-indigo-600 focus:outline-none focus:shadow-outline">
              LEARN MORE NOW
            </NuxtLink>
          </div>
          <div class="w-full">
            <div class="mx-3">
              <div class="flex justify-start items-center">
                <img class="w-full max-w-[150px]  h-full min-h-[150px] "
                  src="https://www.everywoman.com/wp-content/uploads/2022/02/laughing-girl-showing-thumbs-up-picture-id505175324.jpg"
                  alt="">
                <div class="px-3  ">
                  <p class="text-sm font-bold tracking-tight text-gray-900 sm:text-lg">
              <span class="block text-indigo-600">Workflow management</span>
                  </p>
                  <p>
                    Fugiat ipsum ipsum deserunt culpa aute sint do nostrud anim incididunt cillum culpa consequat.
                    Excepteur
                    qui ipsum aliquip consequat sint. Sit id mollit nulla mollit nostrud in ea officia proident. Irure
                    nostrud
                    pariatur mollit ad adipisicing reprehenderit deserunt qui eu.
                  </p>
                </div>
              </div>
            </div>
            <div class="mx-3 my-5">
              <div class="flex justify-start items-center">
                <img class="w-full max-w-[150px]  h-full min-h-[150px] "
                  src="https://www.everywoman.com/wp-content/uploads/2022/02/laughing-girl-showing-thumbs-up-picture-id505175324.jpg"
                  alt="">
                <div class="px-3  ">
                  <p class="text-sm font-bold tracking-tight text-gray-900 sm:text-lg">
              <span class="block text-indigo-600">Workflow management</span>
                  </p>
                  <p>
                    Fugiat ipsum ipsum deserunt culpa aute sint do nostrud anim incididunt cillum culpa consequat.
                    Excepteur
                    qui ipsum aliquip consequat sint. Sit id mollit nulla mollit nostrud in ea officia proident. Irure
                    nostrud
                    pariatur mollit ad adipisicing reprehenderit deserunt qui eu.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>

      </div>
    </section>

    <!-- body -->

  </div>
</template>

<script setup>
import PublicToolbarVue from "../components/PublicToolbar.vue";

const features = [
  {
    name: 'Tips on Project and Task Management',
    description:
      'Lorem ipsum, dolor sit amet consectetur adipisicing elit. Maiores impedit perferendis suscipit eaque, iste dolor cupiditate blanditiis ratione.',
    icon: `<svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
                <path stroke-linecap="round" stroke-linejoin="round" d="M12 21a9.004 9.004 0 008.716-6.747M12 21a9.004 9.004 0 01-8.716-6.747M12 21c2.485 0 4.5-4.03 4.5-9S14.485 3 12 3m0 18c-2.485 0-4.5-4.03-4.5-9S9.515 3 12 3m0 0a8.997 8.997 0 017.843 4.582M12 3a8.997 8.997 0 00-7.843 4.582m15.686 0A11.953 11.953 0 0112 10.5c-2.998 0-5.74-1.1-7.843-2.918m15.686 0A8.959 8.959 0 0121 12c0 .778-.099 1.533-.284 2.253m0 0A17.919 17.919 0 0112 16.5c-3.162 0-6.133-.815-8.716-2.247m0 0A9.015 9.015 0 013 12c0-1.605.42-3.113 1.157-4.418" />
              </svg>`,
  },
  {
    name: 'Workflows',
    description:
      'Lorem ipsum, dolor sit amet consectetur adipisicing elit. Maiores impedit perferendis suscipit eaque, iste dolor cupiditate blanditiis ratione.',
    icon: `<svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
                <path stroke-linecap="round" stroke-linejoin="round" d="M12 3v17.25m0 0c-1.472 0-2.882.265-4.185.75M12 20.25c1.472 0 2.882.265 4.185.75M18.75 4.97A48.416 48.416 0 0012 4.5c-2.291 0-4.545.16-6.75.47m13.5 0c1.01.143 2.01.317 3 .52m-3-.52l2.62 10.726c.122.499-.106 1.028-.589 1.202a5.988 5.988 0 01-2.031.352 5.988 5.988 0 01-2.031-.352c-.483-.174-.711-.703-.59-1.202L18.75 4.971zm-16.5.52c.99-.203 1.99-.377 3-.52m0 0l2.62 10.726c.122.499-.106 1.028-.589 1.202a5.989 5.989 0 01-2.031.352 5.989 5.989 0 01-2.031-.352c-.483-.174-.711-.703-.59-1.202L5.25 4.971z" />
              </svg>`,
  },
  {
    name: 'Tips on Graduation Project',
    description:
      'Lorem ipsum, dolor sit amet consectetur adipisicing elit. Maiores impedit perferendis suscipit eaque, iste dolor cupiditate blanditiis ratione.',
    icon: `<svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
                <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 13.5l10.5-11.25L12 10.5h8.25L9.75 21.75 12 13.5H3.75z" />
              </svg>`,
  },
  {
    name: 'Best practices',
    description:
      'Lorem ipsum, dolor sit amet consectetur adipisicing elit. Maiores impedit perferendis suscipit eaque, iste dolor cupiditate blanditiis ratione.',
    icon: `<svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" aria-hidden="true">
                <path stroke-linecap="round" stroke-linejoin="round" d="M7.5 8.25h9m-9 3H12m-9.75 1.51c0 1.6 1.123 2.994 2.707 3.227 1.129.166 2.27.293 3.423.379.35.026.67.21.865.501L12 21l2.755-4.133a1.14 1.14 0 01.865-.501 48.172 48.172 0 003.423-.379c1.584-.233 2.707-1.626 2.707-3.228V6.741c0-1.602-1.123-2.995-2.707-3.228A48.394 48.394 0 0012 3c-2.392 0-4.744.175-7.043.513C3.373 3.746 2.25 5.14 2.25 6.741v6.018z" />
              </svg>`,
  },
]
</script>
