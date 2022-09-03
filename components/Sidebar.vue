<template>
  <div>
    <!-- Sidebar -->
    <div
      class="
        hidden
        md:block
        fixed
        flex flex-col
        left-0
        w-14
        hover:w-64
        md:w-64
        h-full
        transition-all
        duration-300
        border-r
        bg-white
        z-10
        sidebar
      "
    >
      <div
        class="
          overflow-y-auto overflow-x-hidden
          flex flex-col
          justify-between
          flex-grow
        "
      >
        <ul class="flex flex-col py-4 pt-0 space-y-1">
          <li class="px-5 pt-5 hidden md:block">
            <div class="flex flex-row items-center h-8">
              <div
                class="text-sm font-light tracking-wide text-gray-400 uppercase"
              >
                Workflow Management
              </div>
            </div>
          </li>
          <li>
            <a
              href="#"
              class="
                relative
                flex flex-row
                items-center
                h-11
                focus:outline-none
                hover:bg-white-800
                dark:hover:bg-white-600
                bg-black-600
                hover:bg-black-800
                border-l-4 border-transparent
                hover:border-blue-500
                dark:hover:border-gray-800
                pr-6
              "
            >
              <span class="inline-flex justify-center items-center ml-4">
                <svg
                  class="w-5 h-5"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"
                  ></path>
                </svg>
              </span>
              <span class="ml-2 text-sm tracking-wide truncate">Home</span>
            </a>
          </li>
          <li>
            <a
              href="#"
              class="
                relative
                flex flex-row
                items-center
                h-11
                focus:outline-none
                hover:bg-white-800
                dark:hover:bg-white-600
                bg-black-600
                hover:bg-black-800
                border-l-4 border-transparent
                hover:border-blue-500
                dark:hover:border-gray-800
                pr-6
              "
            >
              <span class="inline-flex justify-center items-center ml-4">
                <svg
                  class="w-5 h-5"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9"
                  ></path>
                </svg>
              </span>
              <span class="ml-2 text-sm tracking-wide truncate"
                >Notifications</span
              >
              <span
                class="
                  hidden
                  md:block
                  px-2
                  py-0.5
                  ml-auto
                  text-xs
                  font-medium
                  tracking-wide
                  text-red-500
                  bg-red-50
                  rounded-full
                "
                >1.2k</span
              >
            </a>
          </li>
          <li>
            <a
              href="#"
              class="
                relative
                flex flex-row
                items-center
                h-11
                focus:outline-none
                hover:bg-white-800
                dark:hover:bg-white-600
                bg-black-600
                hover:bg-black-800
                border-l-4 border-transparent
                hover:border-blue-500
                dark:hover:border-gray-800
                pr-6
              "
            >
              <span class="inline-flex justify-center items-center ml-4">
                <svg
                  class="w-5 h-5"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M7 8h10M7 12h4m1 8l-4-4H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-3l-4 4z"
                  ></path>
                </svg>
              </span>
              <span class="ml-2 text-sm tracking-wide truncate">Messages</span>
              <span
                class="
                  hidden
                  md:block
                  px-2
                  py-0.5
                  ml-auto
                  text-xs
                  font-medium
                  tracking-wide
                  text-red-500
                  bg-red-50
                  rounded-full
                "
                >21</span
              >
            </a>
          </li>
          <li>
            <a
              href="#"
              class="
                relative
                flex flex-row
                items-center
                h-11
                focus:outline-none
                hover:bg-white-800
                dark:hover:bg-white-600
                bg-black-600
                hover:bg-black-800
                border-l-4 border-transparent
                hover:border-blue-500
                dark:hover:border-gray-800
                pr-6
              "
            >
              <span class="inline-flex justify-center items-center ml-4">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-6 w-6"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"
                  />
                </svg>
              </span>
              <span class="ml-2 text-sm tracking-wide truncate">My Day</span>
              <span
                class="
                  hidden
                  md:block
                  px-2
                  py-0.5
                  ml-auto
                  text-xs
                  font-medium
                  tracking-wide
                  rounded-md
                "
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5"
                  viewBox="0 0 20 20"
                  fill="#2196f3"
                >
                  <path
                    fill-rule="evenodd"
                    d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z"
                    clip-rule="evenodd"
                  />
                </svg>
              </span>
            </a>
          </li>
          <li>
            <a
              href="#"
              class="
                relative
                flex flex-row
                items-center
                h-11
                focus:outline-none
                hover:bg-white-800
                dark:hover:bg-white-600
                bg-black-600
                hover:bg-black-800
                border-l-4 border-transparent
                hover:border-blue-500
                dark:hover:border-gray-800
                pr-6
              "
            >
              <span class="inline-flex justify-center items-center ml-1">
                <!-- <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5"
                  viewBox="0 0 24 24"
                >
                  <path d="M10,17L15,12L10,7V17Z" />
                </svg> -->
                <svg
                  class="h-5 w-5"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                >
                  <path d="M7,10L12,15L17,10H7Z" />
                </svg>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5"
                  viewBox="0 0 20 20"
                  fill="#2196f3"
                >
                  <path
                    fill-rule="evenodd"
                    d="M4 4a2 2 0 00-2 2v8a2 2 0 002 2h12a2 2 0 002-2V8a2 2 0 00-2-2h-5L9 4H4zm7 5a1 1 0 10-2 0v1H8a1 1 0 100 2h1v1a1 1 0 102 0v-1h1a1 1 0 100-2h-1V9z"
                  />
                </svg>
              </span>
              <span class="ml-2 text-sm tracking-wide truncate"
                >Project Name</span
              >
              <span
                class="
                  hidden
                  md:block
                  px-2
                  py-0.5
                  ml-auto
                  text-xs
                  font-medium
                  tracking-wide
                  rounded-md
                "
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5"
                  fill="#2196f3"
                  viewBox="0 0 24 24"
                  stroke="#2196f3"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M12 4v16m8-8H4"
                  /></svg
              ></span>
            </a>
            <div class="ml-3">
              <ul class="flex flex-col pt-0 space-y-1">
                <li>
                  <a
                    href="#"
                    class="
                      relative
                      flex flex-row
                      items-center
                      h-8
                      focus:outline-none
                      hover:bg-white-800
                      dark:hover:bg-white-600
                      bg-black-600
                      hover:bg-black-800
                      border-l-4 border-transparent
                      hover:border-blue-500
                      dark:hover:border-gray-800
                      pr-6
                    "
                  >
                    <span class="inline-flex justify-center items-center ml-4">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        class="h-6 w-6"
                        fill="none"
                        viewBox="0 0 24 24"
                        stroke="currentColor"
                        stroke-width="2"
                      >
                        <path
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"
                        />
                      </svg>
                    </span>
                    <span class="ml-2 text-sm tracking-wide truncate"
                      >Product Management</span
                    >
                  </a>
                </li>
                <li>
                  <a
                    href="#"
                    class="
                      relative
                      flex flex-row
                      items-center
                      h-8
                      focus:outline-none
                      hover:bg-white-800
                      dark:hover:bg-white-600
                      bg-black-600
                      hover:bg-black-800
                      border-l-4 border-transparent
                      hover:border-blue-500
                      dark:hover:border-gray-800
                      pr-6
                    "
                  >
                    <span class="inline-flex justify-center items-center ml-4">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        class="h-5 w-5"
                        viewBox="0 0 20 20"
                        fill="currentColor"
                      >
                        <path
                          d="M13 6a3 3 0 11-6 0 3 3 0 016 0zM18 8a2 2 0 11-4 0 2 2 0 014 0zM14 15a4 4 0 00-8 0v3h8v-3zM6 8a2 2 0 11-4 0 2 2 0 014 0zM16 18v-3a5.972 5.972 0 00-.75-2.906A3.005 3.005 0 0119 15v3h-3zM4.75 12.094A5.973 5.973 0 004 15v3H1v-3a3 3 0 013.75-2.906z"
                        />
                      </svg>
                    </span>
                    <span class="ml-2 text-sm tracking-wide truncate"
                      >Meetings and Notes</span
                    >
                  </a>
                </li>
                <li>
                  <a
                    href="#"
                    class="
                      relative
                      flex flex-row
                      items-center
                      h-8
                      focus:outline-none
                      hover:bg-white-800
                      dark:hover:bg-white-600
                      bg-black-600
                      hover:bg-black-800
                      border-l-4 border-transparent
                      hover:border-blue-500
                      dark:hover:border-gray-800
                      pr-6
                    "
                  >
                    <span class="inline-flex justify-center items-center ml-4">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        class="h-6 w-6"
                        fill="none"
                        viewBox="0 0 24 24"
                        stroke="currentColor"
                        stroke-width="2"
                      >
                        <path
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          d="M5 19a2 2 0 01-2-2V7a2 2 0 012-2h4l2 2h4a2 2 0 012 2v1M5 19h14a2 2 0 002-2v-5a2 2 0 00-2-2H9a2 2 0 00-2 2v5a2 2 0 01-2 2z"
                        />
                      </svg>
                    </span>
                    <span class="ml-2 text-sm tracking-wide truncate"
                      >Sprints and Backlog</span
                    >
                  </a>
                </li>
                <li>
                  <a
                    href="#"
                    class="
                      relative
                      flex flex-row
                      items-center
                      h-8
                      focus:outline-none
                      hover:bg-white-800
                      dark:hover:bg-white-600
                      bg-black-600
                      hover:bg-black-800
                      border-l-4 border-transparent
                      hover:border-blue-500
                      dark:hover:border-gray-800
                      pr-6
                    "
                  >
                    <span class="inline-flex justify-center items-center ml-4">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        class="h-5 w-5"
                        viewBox="0 0 20 20"
                        fill="currentColor"
                      >
                        <path
                          fill-rule="evenodd"
                          d="M10 18a8 8 0 100-16 8 8 0 000 16zM7 9H5v2h2V9zm8 0h-2v2h2V9zM9 9h2v2H9V9z"
                          clip-rule="evenodd"
                        />
                      </svg>
                    </span>
                    <span class="ml-2 text-sm tracking-wide truncate"
                      >Sprint Standups</span
                    >
                  </a>
                </li>
                <li>
                  <a
                    href="#"
                    class="
                      relative
                      flex flex-row
                      items-center
                      h-8
                      focus:outline-none
                      hover:bg-white-800
                      dark:hover:bg-white-600
                      bg-black-600
                      hover:bg-black-800
                      border-l-4 border-transparent
                      hover:border-blue-500
                      dark:hover:border-gray-800
                      pr-6
                    "
                  >
                    <span class="inline-flex justify-center items-center ml-4">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        class="h-5 w-5"
                        viewBox="0 0 20 20"
                        fill="currentColor"
                      >
                        <path
                          d="M9 2a2 2 0 00-2 2v8a2 2 0 002 2h6a2 2 0 002-2V6.414A2 2 0 0016.414 5L14 2.586A2 2 0 0012.586 2H9z"
                        />
                        <path
                          d="M3 8a2 2 0 012-2v10h8a2 2 0 01-2 2H5a2 2 0 01-2-2V8z"
                        />
                      </svg>
                    </span>
                    <span class="ml-2 text-sm tracking-wide truncate"
                      >Resources</span
                    >
                  </a>
                </li>
                <li>
                  <a
                    href="#"
                    class="
                      relative
                      flex flex-row
                      items-center
                      h-8
                      focus:outline-none
                      hover:bg-white-800
                      dark:hover:bg-white-600
                      bg-black-600
                      hover:bg-black-800
                      border-l-4 border-transparent
                      hover:border-blue-500
                      dark:hover:border-gray-800
                      pr-6
                    "
                  >
                    <span class="inline-flex justify-center items-center ml-4">
                      <svg
                        xmlns="http://www.w3.org/2000/svg"
                        class="h-5 w-5"
                        viewBox="0 0 20 20"
                        fill="currentColor"
                      >
                        <path
                          fill-rule="evenodd"
                          d="M6.267 3.455a3.066 3.066 0 001.745-.723 3.066 3.066 0 013.976 0 3.066 3.066 0 001.745.723 3.066 3.066 0 012.812 2.812c.051.643.304 1.254.723 1.745a3.066 3.066 0 010 3.976 3.066 3.066 0 00-.723 1.745 3.066 3.066 0 01-2.812 2.812 3.066 3.066 0 00-1.745.723 3.066 3.066 0 01-3.976 0 3.066 3.066 0 00-1.745-.723 3.066 3.066 0 01-2.812-2.812 3.066 3.066 0 00-.723-1.745 3.066 3.066 0 010-3.976 3.066 3.066 0 00.723-1.745 3.066 3.066 0 012.812-2.812zm7.44 5.252a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                          clip-rule="evenodd"
                        />
                      </svg>
                    </span>
                    <span class="ml-2 text-sm tracking-wide truncate"
                      >Definition of Done</span
                    >
                  </a>
                </li>
                <li>
                  <a
                    href="#"
                    class="
                      relative
                      flex flex-row
                      items-center
                      h-8
                      focus:outline-none
                      hover:bg-white-800
                      dark:hover:bg-white-600
                      bg-black-600
                      hover:bg-black-800
                      border-l-4 border-transparent
                      hover:border-blue-500
                      dark:hover:border-gray-800
                      pr-6
                    "
                  >
                    <span
                      class="
                        inline-flex
                        justify-center
                        items-center
                        ml-4
                        bg-pink-900
                        rounded-sm
                      "
                    >
                      <svg
                        class="h-6 w-6 text-white"
                        width="24"
                        height="24"
                        viewBox="0 0 24 24"
                        stroke-width="2"
                        stroke="currentColor"
                        fill="none"
                        stroke-linecap="round"
                        stroke-linejoin="round"
                      >
                        <path stroke="none" d="M0 0h24v24H0z" />
                        <path d="M9 9v-1a3 3 0 0 1 6 0v1" />
                        <path
                          d="M8 9h8a6 6 0 0 1 1 3v3a5 5 0 0 1 -10 0v-3a6 6 0 0 1 1 -3"
                        />
                        <line x1="3" y1="13" x2="7" y2="13" />
                        <line x1="17" y1="13" x2="21" y2="13" />
                        <line x1="12" y1="20" x2="12" y2="14" />
                        <line x1="4" y1="19" x2="7.35" y2="17" />
                        <line x1="20" y1="19" x2="16.65" y2="17" />
                        <line x1="4" y1="7" x2="7.75" y2="9.4" />
                        <line x1="20" y1="7" x2="16.25" y2="9.4" />
                      </svg>
                    </span>
                    <span class="ml-2 text-sm tracking-wide truncate"
                      >Bugs</span
                    >
                  </a>
                </li>
              </ul>
            </div>
          </li>
        </ul>
        <div class="mb-14 px-5 py-3 hidden md:block text-center text-xs">
          <ul>
            <li class="px-5 hidden md:block">
              <div class="flex flex-row items-center mt-5 h-8">
                <div
                  class="
                    text-sm
                    font-light
                    tracking-wide
                    text-gray-400
                    uppercase
                  "
                >
                  Settings
                </div>
              </div>
            </li>
            <li>
              <a
                href="#"
                class="
                  relative
                  flex flex-row
                  items-center
                  h-11
                  focus:outline-none
                  hover:bg-white-800
                  dark:hover:bg-white-600
                  bg-black-600
                  hover:bg-black-800
                  border-l-4 border-transparent
                  hover:border-blue-500
                  dark:hover:border-gray-800
                  pr-6
                "
              >
                <span class="inline-flex justify-center items-center ml-4">
                  <svg
                    class="w-5 h-5"
                    fill="none"
                    stroke="currentColor"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"
                    ></path>
                  </svg>
                </span>
                <span class="ml-2 text-sm tracking-wide truncate">Profile</span>
              </a>
            </li>
            <li>
              <a
                href="#"
                class="
                  relative
                  flex flex-row
                  items-center
                  h-11
                  focus:outline-none
                  hover:bg-white-800
                  dark:hover:bg-white-600
                  bg-black-600
                  hover:bg-black-800
                  border-l-4 border-transparent
                  hover:border-blue-500
                  dark:hover:border-gray-800
                  pr-6
                "
              >
                <span class="inline-flex justify-center items-center ml-4">
                  <svg
                    class="w-5 h-5"
                    fill="none"
                    stroke="currentColor"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z"
                    ></path>
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"
                    ></path>
                  </svg>
                </span>
                <span class="ml-2 text-sm tracking-wide truncate"
                  >Settings</span
                >
              </a>
            </li>
          </ul>
        </div>
      </div>
    </div>
    <!-- ./Sidebar -->
  </div>
</template>