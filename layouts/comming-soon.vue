<template>
    <div class="h-screen flex justify-center items-center text-center bg-[#0F172A]">
  
      <div>
        <slot />
      </div>
      <Footer />
      <!-- <Banner /> -->


    </div>
  </template>
  
  <script setup>
  import Footer from "@/components/comming-soon/footer.vue";
  // import Banner from "@/components/comming-soon/banner.vue";

  </script>
  
  <style scoped></style>
  