<template>
    <div>
        <div class="flex px-6 py-6">
            <button @click="sidebarOpen = true" class="text-gray-500 focus:outline-none lg:hidden mr-3">
                <svg class="h-6 w-6" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M4 6H20M4 12H20M4 18H11" stroke="currentColor" stroke-width="2"
                          stroke-linecap="round"
                          stroke-linejoin="round"></path>
                </svg>
            </button>

            <div class="flex-auto">
                <p class="text-gray-800 text-3xl font-medium">Dashboard </p>
            </div>

            <div class="flex-auto">
                <div class="relative mx-4 lg:mx-0">
                    <input class="w-50 sm:w-64 rounded-md pl-10 pr-4 focus:border-indigo-600" type="text"
                           placeholder="Search">

                    <span class="absolute inset-y-0 left-0 pl-3 flex items-center">
                            <svg class="h-5 w-5 text-gray-500" viewBox="0 0 24 24" fill="none">
                                <path
                                    d="M21 21L15 15M17 10C17 13.866 13.866 17 10 17C6.13401 17 3 13.866 3 10C3 6.13401 6.13401 3 10 3C13.866 3 17 6.13401 17 10Z"
                                    stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                    stroke-linejoin="round">
                                </path>
                            </svg>
                        </span>
                </div>
            </div>

        </div>
    </div>
</template>
