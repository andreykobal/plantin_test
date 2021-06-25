<template>
<header class="fixed w-full">
<nav class="bg-white shadow-lg">
<div class="max-w-7xl mx-auto px-2 sm:px-6 lg:px-8">
  <div class="relative flex items-center justify-between h-16">
    <div class="absolute inset-y-0 left-0 flex items-center sm:hidden">
      <button type="button" class="inline-flex items-center justify-center p-2 rounded-md text-gray-400 hover:text-gray-700 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-white" aria-controls="mobile-menu" aria-expanded="false">
        <span class="sr-only">Open main menu</span>

        <svg class="block h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
        </svg>

        <svg class="hidden h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
        </svg>
      </button>
    </div>
    <div class="flex-1 flex items-center justify-center sm:items-stretch sm:justify-start">

      <div class="hidden sm:block sm:ml-6">
        <div class="flex space-x-4">
          <a href="#" class="text-gray-700 hover:bg-gray-100 hover:text-gray-700 px-3 py-2 rounded-md text-sm font-medium" >Discover</a>

          <a href="#" class="text-gray-700 hover:bg-gray-100 hover:text-gray-700 px-3 py-2 rounded-md text-sm font-medium">My Plants</a>

          <a href="#" class="text-gray-700 hover:bg-gray-100 hover:text-gray-700 px-3 py-2 rounded-md text-sm font-medium">Diseases</a>

          <a href="#" class="bg-gray-100  text-gray-700 hover:bg-gray-100 hover:text-gray-700 px-3 py-2 rounded-md text-sm font-medium" aria-current="page">Blog</a>

          <a href="#" class="text-gray-700 hover:bg-gray-100 hover:text-gray-700 px-3 py-2 rounded-md text-sm font-medium">FAQ</a>

          <a href="#" class="text-gray-700 hover:bg-gray-100 hover:text-gray-700 px-3 py-2 rounded-md text-sm font-medium">Contact Us</a>
        </div>
      </div>
    </div>
    <div class="absolute inset-y-0 right-0 flex items-center pr-2 sm:static sm:inset-auto sm:ml-6 sm:pr-0">
      <button class="bg-white p-1 rounded-full text-gray-400 hover:text-gray-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-offset-gray-800 focus:ring-white">
        <span class="sr-only">View notifications</span>
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
        </svg>
      </button>

      <div class="ml-3 relative">
        <div>
          <button type="button" class="bg-white flex text-sm rounded-full focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-offset-gray-800 focus:ring-white" id="user-menu-button" aria-expanded="false" aria-haspopup="true">
            <span class="sr-only">Open user menu</span>
            <img class="h-8 w-8 rounded-full" src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="">
          </button>
        </div>

        <div class="origin-top-right absolute right-0 mt-2 w-48 rounded-md shadow-lg py-1 bg-white ring-1 ring-black ring-opacity-5 focus:outline-none" role="menu" aria-orientation="vertical" aria-labelledby="user-menu-button" tabindex="-1">
          <a href="#" class="block px-4 py-2 text-sm text-gray-700" role="menuitem" tabindex="-1" id="user-menu-item-0">Your Profile</a>
          <a href="#" class="block px-4 py-2 text-sm text-gray-700" role="menuitem" tabindex="-1" id="user-menu-item-1">Settings</a>
          <a href="#" class="block px-4 py-2 text-sm text-gray-700" role="menuitem" tabindex="-1" id="user-menu-item-2">Sign out</a>
        </div>
      </div>
    </div>
  </div>
</div>

<!--<div class="sm:hidden" id="mobile-menu">
  <div class="px-2 pt-2 pb-3 space-y-1">

    <a href="#" class="text-gray-700 hover:bg-gray-100 hover:text-gray-700 block px-3 py-2 rounded-md text-base font-medium">Team</a>

    <a href="#" class="text-gray-700 hover:bg-gray-100 hover:text-gray-700 block px-3 py-2 rounded-md text-base font-medium">Projects</a>

    <a href="#" class="text-gray-700 hover:bg-gray-100 hover:text-gray-700 block px-3 py-2 rounded-md text-base font-medium">Calendar</a>

    <a href="#" class="bg-gray-100 text-gray-700 block px-3 py-2 rounded-md text-base font-medium" aria-current="page">Blog</a>

  </div>
</div>-->
</nav>

</header>
</template>