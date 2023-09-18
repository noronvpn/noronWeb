<template>
  <!-- <NuxtLoadingIndicator :height="0" :throttle="0" :duration="0"> -->
  <!-- <loading /> -->
  <!-- </NuxtLoadingIndicator> -->
  <div>
    <div class="sticky top-0 z-10">
      <Header />
    </div>

    <div class="bg-white relative dark:bg-[#0F172A]">
      <slot />
    </div>

    <div class="relative z-10">
      <Footer />
    </div>
  </div>
</template>

<script setup>
import Header from "@/components/landing/comming-soon/header.vue";
import Footer from "@/components/landing/comming-soon/footer.vue";
</script>

<style scoped></style>
