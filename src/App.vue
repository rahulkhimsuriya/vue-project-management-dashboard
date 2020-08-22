<template>
  <div id="app" class="bg-white">
    <aside class="w-56 border-r">
      <header class="flex flex-col justify-between min-h-screen">
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
    <main></main>
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
