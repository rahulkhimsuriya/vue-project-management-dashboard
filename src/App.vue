<template>
  <div id="app" class="bg-white flex min-h-screen">
    <aside class="w-64 border-r">
      <header class="flex flex-col justify-between h-full">
        <div class="mt-6">
          <h1 class="px-6 text-3xl font-bold">S</h1>

          <nav class="mt-8 px-4">
            <a
              href="#"
              class="px-4 py-2 flex bg-gray-100 text-center text-base text-gray-800 rounded-full"
            >
              <span class="mr-2">
                <svg
                  class="h-6 w-6"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M22.75 13h-4.3333l-3.25 8.6667-4.3334-17.33336L7.58333 13H3.25"
                    stroke="#202842"
                    stroke-width="1.625"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                  />
                </svg>
              </span>
              Dashboard
            </a>
            <a
              href="#"
              class="mt-2 px-4 py-2 flex hover:bg-gray-100 text-center text-base text-gray-800 rounded-full"
            >
              <span class="mr-2">
                <svg
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  class="w-6 h-6"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M3 7v10a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2h-6l-2-2H5a2 2 0 00-2 2z"
                  />
                </svg>
              </span>
              Folders
            </a>
            <a
              href="#"
              class="mt-2 px-4 py-2 flex hover:bg-gray-100 text-center text-base text-gray-800 rounded-full"
            >
              <span class="mr-2">
                <svg
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  class="w-6 h-6"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M8 16H6a2 2 0 01-2-2V6a2 2 0 012-2h8a2 2 0 012 2v2m-6 12h8a2 2 0 002-2v-8a2 2 0 00-2-2h-8a2 2 0 00-2 2v8a2 2 0 002 2z"
                  />
                </svg>
              </span>
              Projects
            </a>
            <a
              href="#"
              class="mt-2 px-4 py-2 flex hover:bg-gray-100 text-center text-base text-gray-800 rounded-full"
            >
              <span class="mr-2">
                <svg
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  class="clipboard-check w-6 h-6"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-6 9l2 2 4-4"
                  />
                </svg>
              </span>
              Tasks
            </a>
            <a
              href="#"
              class="mt-2 px-4 py-2 flex hover:bg-gray-100 text-center text-base text-gray-800 rounded-full"
            >
              <span class="mr-2">
                <svg
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  class="w-6 h-6"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z"
                  />
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"
                  />
                </svg>
              </span>
              Settings
            </a>
          </nav>
        </div>

        <div
          class=" px-4 py-4 border border-r-0 flex justify-between items-center"
        >
          <div class="flex items-center">
            <img
              src="./assets/profile.png"
              alt="profile"
              class="h-10 w-10 rounded-full object-cover"
            />
            <p class="ml-2 font-semibold text-gray-900">Devin Lee</p>
          </div>

          <a
            href="#"
            class="p-1 bg-blue-100 group hover:text-white hover:bg-blue-400 rounded-full"
          >
            <svg
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              class="h-4 w-4 text-blue-400 group-hover:text-white"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M9 5l7 7-7 7"
              />
            </svg>
          </a>
        </div>
      </header>
    </aside>
    <main class="px-10 w-full">
      <header class="py-6 flex items-center justify-between">
        <div>
          <div class="relative">
            <span class="absolute inset-y-0 pl-4 py-3 text-gray-400">
              <svg
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                class="w-4 h-4"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
                />
              </svg>
            </span>
            <input
              type="text"
              class="w-64 border pl-10 pr-4 py-2 text-sm leading-none text-gray-800 focus:border-gray-800 focus:bg-gray-100 rounded-lg"
              placeholder="Search"
            />
          </div>
        </div>
        <div class="flex space-x-10">
          <div class="flex space-x-6">
            <a href="#">
              <span>
                <svg
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  class="w-6 h-6 text-gray-800"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="1.5"
                    d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
                  />
                </svg>
              </span>
            </a>
            <a href="#">
              <span>
                <svg
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  class="w-6 h-6 text-gray-800"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="1.5"
                    d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9"
                  ></path>
                </svg>
              </span>
            </a>
          </div>
          <div class="flex flex-col">
            <time
              datetime="17:30"
              class="text-2xl text-gray-900 font-normal leading-none"
              >17:30</time
            >
            <time
              datetime="2020-08-18"
              class="mt-1 text-sm text-gray-900 font-normal leading-none"
              >18 August</time
            >
          </div>
        </div>
      </header>

      <div class="flex gap-6">
        <div class="w-3/5">
          <div>
            <h2 class="text-base font-semibold text-gray-900">
              Recent Folders
            </h2>

            <div class="mt-4 flex space-x-6">
              <div
                class="w-32 h-32 flex flex-col items-center justify-center bg-blue-100 rounded-lg"
              >
                <span>
                  <svg
                    fill="currentColor"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    class="w-16 h-16 text-blue-400"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M3 7v10a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2h-6l-2-2H5a2 2 0 00-2 2z"
                    />
                  </svg>
                </span>
                <p class="text-sm font-semibold text-gray-800">Invoices</p>
              </div>

              <div
                class="w-32 h-32 relative flex flex-col items-center justify-center bg-blue-100 rounded-lg"
              >
                <div
                  class="absolute top-0 right-0 flex items-center justify-center -mt-1 -mr-1 w-4 h-4 bg-white rounded-full"
                >
                  <span class="block w-2 h-2 bg-pink-400 rounded-full"></span>
                </div>

                <span>
                  <svg
                    fill="currentColor"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    class="w-16 h-16 text-blue-400"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M3 7v10a2 2 0 002 2h14a2 2 0 002-2V9a2 2 0 00-2-2h-6l-2-2H5a2 2 0 00-2 2z"
                    />
                  </svg>
                </span>
                <p class="text-sm font-semibold text-gray-800">Customers</p>
              </div>
            </div>
          </div>

          <div class="mt-16">
            <h2 class="text-base font-semibold text-gray-900">
              Projects
            </h2>

            <div class="mt-4 flex items-center justify-between gap-4">
              <div class="w-1/2 p-6 flex bg-blue-100">
                <div
                  class="h-8 flex items-center bg-white text-center rounded-full"
                >
                  <span class="p-3 font-bold text-purple-400">S</span>
                </div>
                <div class="ml-2 w-full">
                  <p class="text-base font-semibold text-gray-900">Sintext</p>
                  <div class="mt-4">
                    <div
                      class="relative w-full h-2 bg-white overflow-hidden rounded-full"
                    >
                      <div
                        class="absolute left-0 top-0 h-full w-9/12 bg-blue-400"
                      ></div>
                    </div>
                    <span class="text-xs font-semibold text-gray-800">
                      26/47
                    </span>
                  </div>
                </div>
              </div>

              <div class="w-1/2 p-6 flex bg-blue-100">
                <div
                  class="h-8 flex items-center bg-white text-center rounded-full"
                >
                  <span class="p-3 font-bold text-red-400">T</span>
                </div>
                <div class="ml-2 w-full">
                  <p class="text-base font-semibold text-gray-900">Tetrion</p>
                  <div class="mt-4">
                    <div
                      class="relative w-full h-2 bg-white overflow-hidden rounded-full"
                    >
                      <div
                        class="absolute left-0 top-0 h-full w-4/12 bg-blue-400"
                      ></div>
                    </div>
                    <span class="text-xs font-semibold text-gray-800">
                      7/21
                    </span>
                  </div>
                </div>
              </div>
            </div>

            <div class="mt-4 flex justify-between gap-4">
              <div class="w-1/2 p-6 flex bg-blue-100">
                <div
                  class="h-8 flex items-center bg-white text-center rounded-full"
                >
                  <span class="p-3 font-bold text-green-400">P</span>
                </div>
                <div class="ml-2 w-full">
                  <p class="text-base font-semibold text-gray-900">Petron</p>
                  <div class="mt-4">
                    <div
                      class="relative w-full h-2 bg-white overflow-hidden rounded-full"
                    >
                      <div
                        class="absolute left-0 top-0 h-full w-11/12 bg-blue-400"
                      ></div>
                    </div>
                    <span class="text-xs font-semibold text-gray-800">
                      12/16
                    </span>
                  </div>
                </div>
              </div>

              <div
                class="w-1/2 p-6 flex flex-col items-center justify-center bg-white border"
              >
                <span>
                  <svg
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                    class="w-6 h-6 text-gray-600"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M12 6v6m0 0v6m0-6h6m-6 0H6"
                    />
                  </svg>
                </span>
                <p class="text-gray-500">Add new</p>
              </div>
            </div>
          </div>
        </div>
        <div class="w-2/5">
          <h2 class="text-base font-semibold text-gray-900">
            YOUR TASKS
          </h2>

          <div class="mt-4 p-4 bg-blue-100 space-y-2 rounded-lg">
            <div class="p-4 bg-white flex rounded">
              <div>
                <span class="block h-4 w-4 border rounded-full"></span>
              </div>
              <div class="ml-2">
                <p class="text-sm font-semibold leading-none text-gray-800">
                  Better quality favicon
                </p>
                <div class="mt-2 flex items-center justify-between">
                  <span
                    class="px-2 py-1 bg-red-400 text-sm text-white leading-none rounded-full"
                  >
                    Design
                  </span>
                </div>
              </div>
            </div>
            <div class="p-4 bg-white flex rounded">
              <div>
                <span class="block h-4 w-4 border rounded-full"></span>
              </div>
              <div class="ml-2 w-full">
                <p class="text-sm font-semibold leading-none text-gray-800">
                  Social accounts setup
                </p>
                <div class="mt-2 flex items-center justify-between">
                  <span
                    class="px-2 py-1 bg-green-400 text-sm text-white leading-none rounded-full"
                  >
                    Marketing
                  </span>

                  <div class="flex items-center justify-center space-x-2">
                    <span>
                      <svg
                        fill="none"
                        viewBox="0 0 24 24"
                        stroke="currentColor"
                        class="w-4 h-4"
                      >
                        <path
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          stroke-width="1.5"
                          d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"
                        />
                      </svg>
                    </span>
                    <time
                      datetime="12:30"
                      class="text-sm text-gray-900 font-normal leading-none"
                      >12:30</time
                    >
                  </div>
                </div>
              </div>
            </div>
            <div class="p-4 bg-white flex rounded">
              <div>
                <span>
                  <svg
                    fill="currentColor"
                    viewBox="0 0 24 24"
                    stroke="#fff"
                    class="w-6 h-6 text-indigo-600"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"
                    />
                  </svg>
                </span>
              </div>
              <div class="ml-2 w-full">
                <p class="text-sm font-semibold leading-none text-gray-800">
                  Upgrade plan page
                </p>
                <div class="mt-2 flex items-center justify-between">
                  <span
                    class="px-2 py-1 bg-purple-400 text-sm text-white leading-none rounded-full"
                  >
                    Development
                  </span>

                  <div class="flex items-center justify-center space-x-2">
                    <span>
                      <svg
                        fill="none"
                        viewBox="0 0 24 24"
                        stroke="currentColor"
                        class="w-4 h-4"
                      >
                        <path
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          stroke-width="1.5"
                          d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"
                        />
                      </svg>
                    </span>
                    <time
                      datetime="14:30"
                      class="text-sm text-gray-900 font-normal leading-none"
                      >14:30</time
                    >
                  </div>
                </div>
              </div>
            </div>
            <div class="p-4 bg-white flex rounded">
              <div>
                <span>
                  <svg
                    fill="currentColor"
                    viewBox="0 0 24 24"
                    stroke="#fff"
                    class="w-6 h-6 text-indigo-600"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"
                    />
                  </svg>
                </span>
              </div>
              <div class="ml-2 w-full">
                <p class="text-sm font-semibold leading-none text-gray-800">
                  Email templates
                </p>
                <div class="mt-2 flex items-center justify-between">
                  <span
                    class="px-2 py-1 bg-red-400 text-sm text-white leading-none rounded-full"
                  >
                    Design
                  </span>

                  <div class="flex items-center justify-center space-x-2">
                    <span>
                      <svg
                        fill="none"
                        viewBox="0 0 24 24"
                        stroke="currentColor"
                        class="w-4 h-4"
                      >
                        <path
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          stroke-width="2"
                          d="M15.172 7l-6.586 6.586a2 2 0 102.828 2.828l6.414-6.586a4 4 0 00-5.656-5.656l-6.415 6.585a6 6 0 108.486 8.486L20.5 13"
                        ></path>
                      </svg>
                    </span>
                    <p class="text-sm text-gray-900 font-normal leading-none">
                      6
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {}
};
</script>

<style>
@import url('./assets/css/tailwind.css');
</style>
