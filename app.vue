<template>
  <div class="text-gray-900 text-sm">
    <nav class="bg-gray-900 text-white px-4 py-3 flex items-center justify-between">
      <div class="flex items-center space-x-4">
        <a href="#" class="text-white hover:text-gray-400">
          <svg aria-hidden="true" viewBox="0 0 24 24"  data-view-component="true" class="w-8 fill-current">
            <path d="M12.5.75C6.146.75 1 5.896 1 12.25c0 5.089 3.292 9.387 7.863 10.91.575.101.79-.244.79-.546 0-.273-.014-1.178-.014-2.142-2.889.532-3.636-.704-3.866-1.35-.13-.331-.69-1.352-1.18-1.625-.402-.216-.977-.748-.014-.762.906-.014 1.553.834 1.769 1.179 1.035 1.74 2.688 1.25 3.349.948.1-.747.402-1.25.733-1.538-2.559-.287-5.232-1.279-5.232-5.678 0-1.25.445-2.285 1.178-3.09-.115-.288-.517-1.467.115-3.048 0 0 .963-.302 3.163 1.179.92-.259 1.897-.388 2.875-.388.977 0 1.955.13 2.875.388 2.2-1.495 3.162-1.179 3.162-1.179.633 1.581.23 2.76.115 3.048.733.805 1.179 1.825 1.179 3.09 0 4.413-2.688 5.39-5.247 5.678.417.36.776 1.05.776 2.128 0 1.538-.014 2.774-.014 3.162 0 .302.216.662.79.547C20.709 21.637 24 17.324 24 12.25 24 5.896 18.854.75 12.5.75Z"></path>
          </svg>
        </a>

        <div class="relative">
          <input type="text" class="rounded bg-gray-700 placeholder-white w-72 px-3 py-1" placeholder="Search or jump to...">
          <div class="absolute top-0 right-0 flex items-center h-full">
            <div class="border border-gray-600 rounded text-xs text-gray-400 px-2 mr-2">/</div>
          </div>
        </div>

        <ul class="flex items-center font-semibold space-x-4">
            <li><a class="hover:text-gray-400" href="#">Pull Requests</a></li>
            <li><a class="hover:text-gray-400" href="#">Issues</a></li>
            <li><a class="hover:text-gray-400" href="#">Marketplace</a></li>
            <li><a class="hover:text-gray-400" href="#">Explore</a></li>
        </ul>
      </div>

      <div class="flex items-center space-x-4 text-white">

        <a href="#" class="relative hover:text-gray-400">
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-5">
            <path stroke-linecap="round" stroke-linejoin="round" d="M14.857 17.082a23.848 23.848 0 0 0 5.454-1.31A8.967 8.967 0 0 1 18 9.75V9A6 6 0 0 0 6 9v.75a8.967 8.967 0 0 1-2.312 6.022c1.733.64 3.56 1.085 5.455 1.31m5.714 0a24.255 24.255 0 0 1-5.714 0m5.714 0a3 3 0 1 1-5.714 0" />
          </svg>
          <div class="bg-blue-600 rounded-full w-2 h-2 absolute top-0 right-0 ">
          </div>
        </a>

        <a href="#" class="flex items-center hover:text-gray-400">

          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-4">
            <path stroke-linecap="round" stroke-linejoin="round" d="M12 4.5v15m7.5-7.5h-15" />
          </svg>

          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-3 ml-1">
            <path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5" />
          </svg>
        </a>

        <a href="#" class="flex items-center hover:text-gray-400">
          <img src="https://avatars.githubusercontent.com/u/115194843?v=4" class="w-5 h-5 rounded-full" alt="Avatar"/>
          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-3 ml-1">
            <path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5" />
          </svg>
        </a>
      </div>
    </nav>
  </div>
</template>
<script setup lang="ts">
</script>