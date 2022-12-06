<template>
  <div>
    <header class="bg-gradient-to-l from-teal-700 via-neutral-400 to-stone-600">
      <nav class="container mx-auto p-4 flex justify-between">
        <nuxt-link to="/" class="font-bold lg:text-5xl">Andromeda</nuxt-link>
        <ul class="flex gap-10 text-2xl">
          <li><nuxt-link to="/">Home</nuxt-link></li>
          <li><nuxt-link to="/about">About</nuxt-link></li>
        </ul>
      </nav>
    </header>
  </div>
</template>

<style scoped>
  .router-link-exact-active {
    color: aqua;
  }
</style>