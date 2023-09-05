<template>
  <div>
    <Navbar />
    <div class="overflow-hidden py-24 sm:py-32 mt-20">
      <div class="">
        <img
        src="https://wallpapercave.com/wp/fIiL0f3.png"
        alt="" class="absolute inset-0 -z-10 h-full w-full object-cover object-right md:object-center opacity-90" />
      </div>
      <div class="mx-auto max-w-7xl px-6 lg:px-8">
        <div class="mx-auto max-w-7xl lg:mx-0">
          <h2 class="text-4xl font-bold tracking-tight text-white sm:text-6xl text-center">Downloads</h2>
          <p class="mt-36 text-lg leading-8 text-gray-300 text-center">This download page offers a hassle-free way to get your hands on this iconic arcade game. 
            Experience the nostalgia and thrill of battling alien invaders on your device with our easy and secure download process.</p>
        </div>
        <div class="mx-auto mt-10 max-w-2xl lg:mx-0 lg:max-w-none">
          <dl class="mt-16 grid grid-cols-1 gap-8 sm:mt-40 sm:grid-cols-2 lg:grid-cols-4">
            <div v-for="stat in stats" :key="stat.name" class="flex flex-col-reverse">
              <dt class="text-base leading-7 text-gray-300">{{ stat.name }}</dt>
              <dd class="text-2xl font-bold leading-9 tracking-tight text-white">{{ stat.value }}</dd>
            </div>
          </dl>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>
const stats = [
  { name: 'Downloads worldwide', value: '0' },
  { name: 'User Ratings', value: '10/10' },
  { name: 'Conversion Rate', value: '0%' },
  { name: 'Daily Active Users', value: '0' },
]
</script>



<style></style>