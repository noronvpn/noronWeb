<template>
  <div class="xl:container m-auto px-6 text-gray-600 dark:text-gray-300 md:px-12 xl:px-6">
    <swiper
      :pagination="{
        dynamicBullets: true,
      }"
      :modules="modules"
      :loop="true"
      :autoplay="{
        delay: 2500,
        disableOnInteraction: false,
      }"
      class="mySwiper"
    >
      <swiper-slide class="!bg-transparent">
        <div class="mx-auto space-y-6 text-center md:w-8/12 lg:w-7/12">
            <img
              class="mx-auto !h-16 !w-16 rounded-full"
              src="https://tailus.io/sources/blocks/tested/preview/images/avatars/first_user.webp"
              alt="user avatar"
              height="220"
              width="220"
              loading="lazy"
            />
            <p>
              <span class="font-serif">"</span> Lorem ipsum dolor sit amet consectetur
              adipisicing elit. Quaerat repellat perspiciatis excepturi est. Non ipsum iusto
              aliquam consequatur repellat provident, omnis ut, sapiente voluptates veritatis
              cum deleniti repudiandae ad doloribus. <span class="font-serif">"</span>
            </p>
            <div>
              <h6 class="text-lg font-semibold leading-none">John Doe</h6>
              <span class="text-xs text-gray-500">Product Designer</span>
            </div>
            <img
              class="mx-auto !w-28"
              src=""
              alt="company logo"
              height="400"
              width="142"
              loading="lazy"
            />
          </div>
      </swiper-slide>
      <swiper-slide>Slide 2</swiper-slide><swiper-slide>Slide 3</swiper-slide>
      <!-- <swiper-slide>Slide 4</swiper-slide><swiper-slide>Slide 5</swiper-slide> -->
      <!-- <swiper-slide>Slide 6</swiper-slide><swiper-slide>Slide 7</swiper-slide> -->
      <!-- <swiper-slide>Slide 8</swiper-slide><swiper-slide>Slide 9</swiper-slide> -->
    </swiper>
  </div>
</template>
<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css";

import "swiper/css/pagination";

// import required modules
import { Autoplay, Pagination } from "swiper/modules";

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Autoplay],
    };
  },
};
</script>
