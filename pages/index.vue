<template>
    <div class="relative font-inter antialiased">

      <main class="relative min-h-screen flex justify-center items-center flex-col bg-slate-900 overflow-hidden">
        <div class="flex justify-center w-3/4">
            <div
              class="relative rounded-full px-3 py-1 text-sm leading-6 text-gray-600 ring-1 ring-indigo-600/10 hover:ring-indigo-600/20"
            >
              Now you can order your vpn with our Telegram Bot.
              <a href="https://noronvpn_bot.t.me" class="font-semibold text-indigo-400"
                ><span class="absolute inset-0" aria-hidden="true" />Go To NoronBot
                <span aria-hidden="true">&rarr;</span></a
              >
            </div>
          </div>
        <div class="w-full max-w-6xl mx-auto px-4 md:px-6 py-24">
            <div class="text-center">

                <!-- Sliding Text animation  -->
                <div
                    class="font-extrabold text-6xl md:text-9xl [text-wrap:balance] bg-clip-text text-transparent bg-gradient-to-r from-slate-200/60 to-50% to-slate-200">
                    Noron <span
                        class="text-indigo-500 inline-flex flex-col h-[calc(theme(fontSize.6xl)*theme(lineHeight.tight))] md:h-[calc(theme(fontSize.9xl)*theme(lineHeight.tight))] overflow-hidden">
                        <span>VPN</span>
                        <!-- <ul class="block animated-text text-left leading-tight [&_li]:block">
                            <li>  Vpn  </li>
                            <li> Safety</li>
                            <li>Support</li>
                            <li aria-hidden="true">Vpn</li>
                        </ul> -->
                    </span></div>
                <!-- End: Sliding Text animation  -->

            </div>

            <p class="font-extrabold text-base [text-wrap:balance] bg-clip-text text-transparent bg-gradient-to-r from-slate-200/60 to-50% to-slate-200"> This Website Is Under Building But You Can Order Your VPN Server With Our <a href="https://noronvpn_bot.t.me" class="text-blue-400 hover:text-blue-600">Telegram Bot</a></p>
          </div>
        </main>
        <!-- <Banner /> -->
</div>
</template>

<script setup>
definePageMeta({
  layout: "comming-soon",
});
</script>
<style scoped>
.animated-text {
    animation-name: text-slide-3; /* Use the desired animation name */
    animation-duration: 7.5s; /* Set the duration of the animation */
    animation-timing-function: cubic-bezier(0.83, 0, 0.17, 1); /* Set the timing function */
    animation-iteration-count: infinite; /* Set the iteration count to make it infinite */
}

@keyframes text-slide-3 {
    0%, 26.66% {
        transform: translateY(0%);
    }
    33.33%, 60% {
        transform: translateY(-25%);
    }
    66.66%, 93.33% {
        transform: translateY(-50%);
    }
    100% {
        transform: translateY(-75%);
    }
}

</style>