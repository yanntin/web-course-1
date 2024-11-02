<template>
  <div class="common-navbar-container w-full flex justify-center">
    <div class="common-navbar flex items-center justify-center px-6 backdrop-blur-sm bg-black/20 rounded-full">
      <nav class="px-4 py-2 flex items-center gap-6">
        <NuxtLink to="/" class="text-white/70 hover:text-white">Home</NuxtLink>
        <div class="w-[1px] h-4 bg-white/30"></div>
        <NuxtLink to="/links" class="text-white/70 hover:text-white">links</NuxtLink>
        <div class="w-[1px] h-4 bg-white/30"></div>
        <NuxtLink to="/about" class="text-white/70 hover:text-white">about</NuxtLink>
      </nav>
    </div>
  </div>
</template>

<style>
.common-navbar-container {
  height: 40px;
  padding-top: 10px;
}

.common-navbar {
  width: 400px;
  height: 30px;
}
</style>
