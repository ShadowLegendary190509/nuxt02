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
        <div class="mx-auto max-w-2xl lg:mx-0">
          <h2 class="text-4xl font-bold tracking-tight text-white sm:text-6xl">Work with us</h2>
          <p class="mt-6 text-lg leading-8 text-gray-300">Anim aute id magna aliqua ad ad non deserunt sunt. Qui irure qui
            lorem cupidatat commodo. Elit sunt amet fugiat veniam occaecat fugiat aliqua.</p>
        </div>
        <div class="mx-auto mt-10 max-w-2xl lg:mx-0 lg:max-w-none">
          <div
            class="grid grid-cols-1 gap-x-8 gap-y-6 text-base font-semibold leading-7 text-white sm:grid-cols-2 md:flex lg:gap-x-10">
            <NuxtLink v-for="link in links" :key="link.name" :href="link.href">{{ link.name }} <span
                aria-hidden="true">&rarr;</span></NuxtLink>
          </div>
          <dl class="mt-16 grid grid-cols-1 gap-8 sm:mt-20 sm:grid-cols-2 lg:grid-cols-4">
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
const links = [
  { name: 'Open roles', href: '#' },
  { name: 'Internship program', href: '#' },
  { name: 'Our values', href: '#' },
  { name: 'Meet our leadership', href: '#' },
]
const stats = [
  { name: 'Offices worldwide', value: '12' },
  { name: 'Full-time colleagues', value: '300+' },
  { name: 'Hours per week', value: '40' },
  { name: 'Paid time off', value: 'Unlimited' },
]
</script>



<style></style>
