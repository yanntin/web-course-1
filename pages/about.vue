<template>
    <div class="pages-waitlist flex flex-col items-center justify-center">
      <FeaturesWaitlistLabelMini />
      <CommonTitlePrimary />
      <FeaturesWaitlistBoxContainer>
        <ContentDoc class="text-gray-300 my-12" />
        <UButton
        to="/"
        class="px-6 bg-white/30 text-white hover:bg-white/50 transition-colors duration-300 relative z-10"
        >回到首页</UButton
      >
      </FeaturesWaitlistBoxContainer>
    </div>
  </template>
<script setup>
</script>

<style>
.pages-waitlist {
  min-height: calc(100vh - 100px);
}
</style>
