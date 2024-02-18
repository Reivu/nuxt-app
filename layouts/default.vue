<template>
  <div>
    <!-- Header -->
    <div>
      <div class="text-3xl font-bold">Nuxt Blog</div>
      <div class="text-lg font-light font-mono flex space-x-4">
        <NuxtLink class="hover:text-cyan-300" to="/">Home</NuxtLink>
        <NuxtLink class="hover:text-cyan-300" :to="{ name: 'contact' }">Contact</NuxtLink>
        <NuxtLink class="hover:text-cyan-300" :to="{ name: 'about' }">About</NuxtLink>
      </div>
    </div>

    <!-- Content -->
    <slot />
  </div>
</template>
