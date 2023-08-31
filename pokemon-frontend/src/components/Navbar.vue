<template>
  <div>
    <nav class="bg-white border-gray-200 dark:bg-gray-900">
      <div class="max-w-screen-2xl flex flex-wrap items-center justify-between mx-auto p-3">
        <a href="https://flowbite.com/" class="">
          <img src="/pokemon.png" class="logo h-8 mr-3" alt="Flowbite Logo" />
        </a>
        <button
          data-collapse-toggle="navbar-default"
          type="button"
          class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
          aria-controls="navbar-default"
          aria-expanded="false"
        >
          <span class="sr-only">Open main menu</span>
          <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 17 14">
            <path
              stroke="currentColor"
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M1 1h15M1 7h15M1 13h15"
            />
          </svg>
        </button>
        <div class="hidden w-full md:block md:w-auto" id="navbar-default">
          <ul
            class="font-medium flex flex-col p-4 md:p-0 mt-4 border border-gray-100 rounded-lg bg-gray-50 md:flex-row md:space-x-8 md:mt-0 md:border-0 md:bg-white dark:bg-gray-800 md:dark:bg-gray-900 dark:border-gray-700"
          >
            <li>
              <router-link to="/tambah-baru">
                <svg xmlns="http://www.w3.org/2000/svg" class="plus" width="50" height="50" viewBox="0 0 40 40" fill="none">
                  <rect x="18" y="4" width="4" height="32" fill="white" />
                  <rect x="4" y="18" width="32" height="4" fill="white" />
                </svg>
              </router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<style scoped>
.plus {
  padding-right: 50%;
  background-color: #e51c23;
}
nav {
  background-color: #e51c23;
}
.logo {
  margin-left: 40%;
  width: 163.057px;
  height: 60px;
}
</style>
