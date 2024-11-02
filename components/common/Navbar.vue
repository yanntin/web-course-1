<template>
  <div class="common-navbar-container w-full flex justify-center">
    <div class="common-navbar flex items-center justify-center px-6 backdrop-blur-sm bg-black/20 rounded-full">
      <nav class="px-4 py-2 flex items-center gap-6">
        <NuxtLink to="/" class="text-white/70 hover:text-white">Home</NuxtLink>
        <div class="w-[1px] h-4 bg-white/30"></div>
        <NuxtLink to="/features" class="text-white/70 hover:text-white">Features</NuxtLink>
        <div class="w-[1px] h-4 bg-white/30"></div>
        <NuxtLink to="/testimonials" class="text-white/70 hover:text-white">Testimonials</NuxtLink>
        <div class="w-[1px] h-4 bg-white/30"></div>
        <NuxtLink to="/faq" class="text-white/70 hover:text-white">FAQ</NuxtLink>
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
  width: 600px;
  height: 30px;
}
</style>
