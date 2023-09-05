<template>
  <div class="bg-white overflow-hidden">
    <Navbar />
    <div class="relative h-full px-6 pt-14 lg:px-8 z-10">
      <div class="">
        <img
        src="https://wallpapercave.com/wp/fIiL0f3.png"
        alt="" class="absolute inset-0 -z-10 h-full w-full object-cover opacity-90"/>
      </div>
      <div class="mx-auto max-w-2xl py-32 sm:py-48 lg:py-56">
        <div class="hidden sm:mb-8 sm:flex sm:justify-center">
          <div
            class="relative rounded-full px-3 py-1 text-sm leading-6 text-gray-100 ring-1 ring-gray-300/10 hover:ring-gray-300/20">
            Newest updates to the game. <NuxtLink href="#" class="font-semibold text-indigo-600"><span
                class="absolute inset-0" aria-hidden="true" />Read more <span aria-hidden="true">&rarr;</span></NuxtLink>
          </div>
        </div>
        <div class="text-center">
          <h1 class="text-4xl font-bold tracking-tight text-gray-100 sm:text-6xl">Welcome to Space Invaders!</h1>
          <p class="mt-6 text-lg leading-8 text-gray-300">The objective of Space Invaders is to manoveur across the screen and shoot descending swarms of aliens, preventing them from reaching the bottom of the screen.  </p>
          <div class="mt-10 flex items-center justify-center gap-x-6">
            <NuxtLink href="#"
              class="rounded-md bg-indigo-600 px-3.5 py-2.5 text-sm font-semibold text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">
              Get started</NuxtLink>
            <NuxtLink href="#" class="text-sm font-semibold leading-6 text-gray-900">Learn more <span
                aria-hidden="true">→</span></NuxtLink>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>

</script>