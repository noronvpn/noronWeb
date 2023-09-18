<template>
  <div class="bg-white container mx-auto dark:bg-[#0F172A]">
    <!-- Header -->
    <section class="h-screen">
      <div class="relative isolate px-6 pt-14 lg:px-8">
        <!-- Announcement -->
        <!-- <div class="flex justify-center">
            <div
              class="relative rounded-full px-3 py-1 text-sm leading-6 text-gray-600 ring-1 ring-gray-900/10 hover:ring-gray-900/20"
            >
              Announcing our next round of funding.
              <a href="#" class="font-semibold text-indigo-600"
                ><span class="absolute inset-0" aria-hidden="true" />Read more
                <span aria-hidden="true">&rarr;</span></a
              >
            </div>
          </div> -->
          <!-- <DetailsBanner :text="sasadad" /> -->

        <div
          class="absolute inset-x-0 -top-40 -z-10 transform-gpu overflow-hidden blur-3xl sm:-top-80"
          aria-hidden="true"
        >
          <div
            class="relative left-[calc(50%-11rem)] aspect-[1155/678] w-[36.125rem] -translate-x-1/2 rotate-[30deg] bg-gradient-to-tr from-[#ff80b5] to-[#9089fc] opacity-30 sm:left-[calc(50%-30rem)] sm:w-[72.1875rem]"
            style="
              clip-path: polygon(
                74.1% 44.1%,
                100% 61.6%,
                97.5% 26.9%,
                85.5% 0.1%,
                80.7% 2%,
                72.5% 32.5%,
                60.2% 62.4%,
                52.4% 68.1%,
                47.5% 58.3%,
                45.2% 34.5%,
                27.5% 76.7%,
                0.1% 64.9%,
                17.9% 100%,
                27.6% 76.8%,
                76.1% 97.7%,
                74.1% 44.1%
              );
            "
          />
        </div>
        <div class="mx-auto max-w-2xl py-32 sm:py-48 lg:py-56">
          <!-- <DetailsBanner :text="sasadad" /> -->



          <div class="text-center">
            <h1
              class="text-4xl font-bold tracking-tight text-gray-900 sm:text-6xl"
            >
              <!-- Data to enrich your online business -->
              <h1
                class="text-9xl font-bold text-indigo-500 dark:text-indigo-500"
              >
                Noron
              </h1>
            </h1>
            <p
              class="mt-6 text-lg leading-8 text-gray-600 dark:text-orange-300"
            >
              Anim aute id magna aliqua ad ad non deserunt sunt. Qui irure qui
              lorem cupidatat commodo. Elit sunt amet fugiat veniam occaecat
              fugiat aliqua.
            </p>
            <div class="mt-10 flex items-center justify-center gap-x-6">
              <a
                href="#"
                class="rounded-md bg-indigo-600 px-3.5 py-2.5 text-sm font-semibold text-white shadow-sm hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600 dark:bg-indigo-700"
                >Get started</a
              >
              <a
                href="#"
                class="text-sm font-semibold leading-6 text-gray-900 dark:text-white"
                >Learn more <span aria-hidden="true">→</span></a
              >
            </div>
          </div>
        </div>
        <div
          class="absolute inset-x-0 top-[calc(100%-13rem)] -z-10 transform-gpu overflow-hidden blur-3xl sm:top-[calc(100%-30rem)]"
          aria-hidden="true"
        >
          <div
            class="relative left-[calc(50%+3rem)] aspect-[1155/678] w-[36.125rem] -translate-x-1/2 bg-gradient-to-tr from-[#ff80b5] to-[#9089fc] opacity-30 sm:left-[calc(50%+36rem)] sm:w-[72.1875rem]"
            style="
              clip-path: polygon(
                74.1% 44.1%,
                100% 61.6%,
                97.5% 26.9%,
                85.5% 0.1%,
                80.7% 2%,
                72.5% 32.5%,
                60.2% 62.4%,
                52.4% 68.1%,
                47.5% 58.3%,
                45.2% 34.5%,
                27.5% 76.7%,
                0.1% 64.9%,
                17.9% 100%,
                27.6% 76.8%,
                76.1% 97.7%,
                74.1% 44.1%
              );
            "
          />
        </div>
      </div>
    </section>
    <!-- cards -->
    <section class="h-screen flex justify-center items-center">
      <Spotlight
        class="max-w-sm mx-auto grid gap-6 lg:grid-cols-3 items-start lg:max-w-none group"
      >
        <!-- Card #1 -->
        <SpotlightCard>
          <div
            class="relative h-full bg-slate-900 p-6 pb-8 rounded-[inherit] z-20 overflow-hidden"
          >
            <!-- Radial gradient -->
            <div
              class="absolute bottom-0 translate-y-1/2 left-1/2 -translate-x-1/2 pointer-events-none -z-10 w-1/2 aspect-square"
              aria-hidden="true"
            >
              <div
                class="absolute inset-0 translate-z-0 bg-slate-800 rounded-full blur-[80px]"
              ></div>
            </div>
            <div class="flex flex-col h-full items-center text-center">
              <!-- Image -->
              <div class="relative inline-flex">
                <div
                  class="w-[40%] h-[40%] absolute inset-0 m-auto -translate-y-[10%] blur-3xl -z-10 rounded-full bg-indigo-600"
                  aria-hidden="true"
                ></div>
                <img
                  class="inline-flex"
                  :src="Card01"
                  width="200"
                  height="200"
                  alt="Card 01"
                />
              </div>
              <!-- Text -->
              <div class="grow mb-5">
                <h2 class="text-xl text-slate-200 font-bold mb-1">
                  Amazing Integration
                </h2>
                <p class="text-sm text-slate-500">
                  Quickly apply filters to refine your issues lists and create
                  custom views.
                </p>
              </div>
              <a
                class="inline-flex justify-center items-center whitespace-nowrap rounded-lg bg-slate-800 hover:bg-slate-900 border border-slate-700 px-3 py-1.5 text-sm font-medium text-slate-300 focus-visible:outline-none focus-visible:ring focus-visible:ring-indigo-300 dark:focus-visible:ring-slate-600 transition-colors duration-150"
                href="#0"
              >
                <svg
                  class="fill-slate-500 mr-2"
                  xmlns="http://www.w3.org/2000/svg"
                  width="16"
                  height="14"
                >
                  <path
                    d="M12.82 8.116A.5.5 0 0 0 12 8.5V10h-.185a3 3 0 0 1-2.258-1.025l-.4-.457-1.328 1.519.223.255A5 5 0 0 0 11.815 12H12v1.5a.5.5 0 0 0 .82.384l3-2.5a.5.5 0 0 0 0-.768l-3-2.5ZM12.82.116A.5.5 0 0 0 12 .5V2h-.185a5 5 0 0 0-3.763 1.708L3.443 8.975A3 3 0 0 1 1.185 10H1a1 1 0 1 0 0 2h.185a5 5 0 0 0 3.763-1.708l4.609-5.267A3 3 0 0 1 11.815 4H12v1.5a.5.5 0 0 0 .82.384l3-2.5a.5.5 0 0 0 0-.768l-3-2.5ZM1 4h.185a3 3 0 0 1 2.258 1.025l.4.457 1.328-1.52-.223-.254A5 5 0 0 0 1.185 2H1a1 1 0 0 0 0 2Z"
                  />
                </svg>
                <span>Connect</span>
              </a>
            </div>
          </div>
        </SpotlightCard>
        <!-- Card #2 -->
        <SpotlightCard>
          <div
            class="relative h-full bg-slate-900 p-6 pb-8 rounded-[inherit] z-20 overflow-hidden"
          >
            <!-- Radial gradient -->
            <div
              class="absolute bottom-0 translate-y-1/2 left-1/2 -translate-x-1/2 pointer-events-none -z-10 w-1/2 aspect-square"
              aria-hidden="true"
            >
              <div
                class="absolute inset-0 translate-z-0 bg-slate-800 rounded-full blur-[80px]"
              ></div>
            </div>
            <div class="flex flex-col h-full items-center text-center">
              <!-- Image -->
              <div class="relative inline-flex">
                <div
                  class="w-[40%] h-[40%] absolute inset-0 m-auto -translate-y-[10%] blur-3xl -z-10 rounded-full bg-indigo-600"
                  aria-hidden="true"
                ></div>
                <img
                  class="inline-flex"
                  :src="Card02"
                  width="200"
                  height="200"
                  alt="Card 02"
                />
              </div>
              <!-- Text -->
              <div class="grow mb-5">
                <h2 class="text-xl text-slate-200 font-bold mb-1">
                  Amazing Integration
                </h2>
                <p class="text-sm text-slate-500">
                  Quickly apply filters to refine your issues lists and create
                  custom views.
                </p>
              </div>
              <a
                class="inline-flex justify-center items-center whitespace-nowrap rounded-lg bg-slate-800 hover:bg-slate-900 border border-slate-700 px-3 py-1.5 text-sm font-medium text-slate-300 focus-visible:outline-none focus-visible:ring focus-visible:ring-indigo-300 dark:focus-visible:ring-slate-600 transition-colors duration-150"
                href="#0"
              >
                <svg
                  class="fill-slate-500 mr-2"
                  xmlns="http://www.w3.org/2000/svg"
                  width="16"
                  height="14"
                >
                  <path
                    d="M12.82 8.116A.5.5 0 0 0 12 8.5V10h-.185a3 3 0 0 1-2.258-1.025l-.4-.457-1.328 1.519.223.255A5 5 0 0 0 11.815 12H12v1.5a.5.5 0 0 0 .82.384l3-2.5a.5.5 0 0 0 0-.768l-3-2.5ZM12.82.116A.5.5 0 0 0 12 .5V2h-.185a5 5 0 0 0-3.763 1.708L3.443 8.975A3 3 0 0 1 1.185 10H1a1 1 0 1 0 0 2h.185a5 5 0 0 0 3.763-1.708l4.609-5.267A3 3 0 0 1 11.815 4H12v1.5a.5.5 0 0 0 .82.384l3-2.5a.5.5 0 0 0 0-.768l-3-2.5ZM1 4h.185a3 3 0 0 1 2.258 1.025l.4.457 1.328-1.52-.223-.254A5 5 0 0 0 1.185 2H1a1 1 0 0 0 0 2Z"
                  />
                </svg>
                <span>Connect</span>
              </a>
            </div>
          </div>
        </SpotlightCard>
        <!-- Card #3 -->
        <SpotlightCard>
          <div
            class="relative h-full bg-slate-900 p-6 pb-8 rounded-[inherit] z-20 overflow-hidden"
          >
            <!-- Radial gradient -->
            <div
              class="absolute bottom-0 translate-y-1/2 left-1/2 -translate-x-1/2 pointer-events-none -z-10 w-1/2 aspect-square"
              aria-hidden="true"
            >
              <div
                class="absolute inset-0 translate-z-0 bg-slate-800 rounded-full blur-[80px]"
              ></div>
            </div>
            <div class="flex flex-col h-full items-center text-center">
              <!-- Image -->
              <div class="relative inline-flex">
                <div
                  class="w-[40%] h-[40%] absolute inset-0 m-auto -translate-y-[10%] blur-3xl -z-10 rounded-full bg-indigo-600"
                  aria-hidden="true"
                ></div>
                <img
                  class="inline-flex"
                  :src="Card03"
                  width="200"
                  height="200"
                  alt="Card 03"
                />
              </div>
              <!-- Text -->
              <div class="grow mb-5">
                <h2 class="text-xl text-slate-200 font-bold mb-1">
                  Amazing Integration
                </h2>
                <p class="text-sm text-slate-500">
                  Quickly apply filters to refine your issues lists and create
                  custom views.
                </p>
              </div>
              <a
                class="inline-flex justify-center items-center whitespace-nowrap rounded-lg bg-slate-800 hover:bg-slate-900 border border-slate-700 px-3 py-1.5 text-sm font-medium text-slate-300 focus-visible:outline-none focus-visible:ring focus-visible:ring-indigo-300 dark:focus-visible:ring-slate-600 transition-colors duration-150"
                href="#0"
              >
                <svg
                  class="fill-slate-500 mr-2"
                  xmlns="http://www.w3.org/2000/svg"
                  width="16"
                  height="14"
                >
                  <path
                    d="M12.82 8.116A.5.5 0 0 0 12 8.5V10h-.185a3 3 0 0 1-2.258-1.025l-.4-.457-1.328 1.519.223.255A5 5 0 0 0 11.815 12H12v1.5a.5.5 0 0 0 .82.384l3-2.5a.5.5 0 0 0 0-.768l-3-2.5ZM12.82.116A.5.5 0 0 0 12 .5V2h-.185a5 5 0 0 0-3.763 1.708L3.443 8.975A3 3 0 0 1 1.185 10H1a1 1 0 1 0 0 2h.185a5 5 0 0 0 3.763-1.708l4.609-5.267A3 3 0 0 1 11.815 4H12v1.5a.5.5 0 0 0 .82.384l3-2.5a.5.5 0 0 0 0-.768l-3-2.5ZM1 4h.185a3 3 0 0 1 2.258 1.025l.4.457 1.328-1.52-.223-.254A5 5 0 0 0 1.185 2H1a1 1 0 0 0 0 2Z"
                  />
                </svg>
                <span>Connect</span>
              </a>
            </div>
          </div>
        </SpotlightCard>
      </Spotlight>
    </section>
    <!-- features -->
    <section class="h-screen flex justify-center items-center">
      <div class="py-16">
        <div class="xl:container m-auto px-6 text-gray-600 md:px-12 xl:px-16">
          <div
            class="lg:bg-gray-50 dark:lg:bg-darker lg:p-16 rounded-[4rem] space-y-6 md:flex flex-row-reverse md:gap-6 justify-center md:space-y-0 lg:items-center dark:bg-black"
          >
            <div class="md:w-5/12 lg:w-1/2 mx-auto text-center">
              <div class="flex items-center justify-center">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="300"
                  height="300"
                  viewBox="0 0 24 24"
                  fill="#1e1b4b"
                >
                  <path
                    d="M12 2C6.486 2 2 6.486 2 12v4.143C2 17.167 2.897 18 4 18h1a1 1 0 0 0 1-1v-5.143a1 1 0 0 0-1-1h-.908C4.648 6.987 7.978 4 12 4s7.352 2.987 7.908 6.857H19a1 1 0 0 0-1 1V18c0 1.103-.897 2-2 2h-2v-1h-4v3h6c2.206 0 4-1.794 4-4 1.103 0 2-.833 2-1.857V12c0-5.514-4.486-10-10-10z"
                  />
                </svg>
              </div>
            </div>

            <div class="md:7/12 lg:w-1/2">
              <h2
                class="text-3xl font-bold text-gray-900 md:text-4xl dark:text-white"
              >
                Noron Support Team
              </h2>
              <p class="my-8 text-gray-600 dark:text-gray-300">
                The Noron Support Team is always there for you and you can
                connect them whenever you need help.
              </p>
              <div
                class="divide-y space-y-4 divide-gray-100 dark:divide-gray-800"
              >
                <div class="mt-8 flex gap-4 md:items-center">
                  <div
                    class="w-12 h-12 flex gap-4 rounded-full bg-indigo-100 dark:bg-indigo-900/20"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      viewBox="0 0 24 24"
                      fill="currentColor"
                      class="w-6 h-6 m-auto text-indigo-500 dark:text-indigo-400"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M4.848 2.771A49.144 49.144 0 0112 2.25c2.43 0 4.817.178 7.152.52 1.978.292 3.348 2.024 3.348 3.97v6.02c0 1.946-1.37 3.678-3.348 3.97a48.901 48.901 0 01-3.476.383.39.39 0 00-.297.17l-2.755 4.133a.75.75 0 01-1.248 0l-2.755-4.133a.39.39 0 00-.297-.17 48.9 48.9 0 01-3.476-.384c-1.978-.29-3.348-2.024-3.348-3.97V6.741c0-1.946 1.37-3.68 3.348-3.97zM6.75 8.25a.75.75 0 01.75-.75h9a.75.75 0 010 1.5h-9a.75.75 0 01-.75-.75zm.75 2.25a.75.75 0 000 1.5H12a.75.75 0 000-1.5H7.5z"
                        clip-rule="evenodd"
                      />
                    </svg>
                  </div>
                  <div class="w-5/6">
                    <h4
                      class="font-semibold text-lg text-gray-700 dark:text-indigo-300"
                    >
                      Chat Anytime
                    </h4>
                    <p class="text-gray-500 dark:text-gray-400">
                      Asperiores nemo possimus nesciunt quam mollitia.
                    </p>
                  </div>
                </div>
                <div class="pt-4 flex gap-4 md:items-center">
                  <div
                    class="w-12 h-12 flex gap-4 rounded-full bg-teal-100 dark:bg-teal-900/20"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      viewBox="0 0 24 24"
                      fill="currentColor"
                      class="w-6 h-6 m-auto text-teal-600 dark:text-teal-400"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M11.54 22.351l.07.04.028.016a.76.76 0 00.723 0l.028-.015.071-.041a16.975 16.975 0 001.144-.742 19.58 19.58 0 002.683-2.282c1.944-1.99 3.963-4.98 3.963-8.827a8.25 8.25 0 00-16.5 0c0 3.846 2.02 6.837 3.963 8.827a19.58 19.58 0 002.682 2.282 16.975 16.975 0 001.145.742zM12 13.5a3 3 0 100-6 3 3 0 000 6z"
                        clip-rule="evenodd"
                      />
                    </svg>
                  </div>
                  <div class="w-5/6">
                    <h4
                      class="font-semibold text-lg text-gray-700 dark:text-teal-300"
                    >
                      Open A Ticket On Our Telegram Robot
                    </h4>
                    <p class="text-gray-500 dark:text-gray-400">
                      Feel free to describe your problem we will help you ASAP.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Comments -->
    <section class="h-screen flex justify-center items-center">
      <FancyTestimonialsSlider :testimonials="testimonials" />
    </section>

    <!-- FAQ -->
    <section class="w-full">
      <BaseSection>
        <div
          data-aos="fade-right"
          data-aos-delay="150"
          class="col-span-12 lg:col-span-6"
        >
          <div class="w-full">
            <img src="@/assets/gifs/noron-bg.gif" class="w-full" alt="" />
          </div>
        </div>
        <div
          data-aos="fade-left"
          data-aos-delay="150"
          class="col-span-12 lg:col-span-6 px-4 sm:px-6 mt-8"
        >
          <span
            class="text-base text-gradient font-semibold uppercase mb-4 sm:mb-2 dark:text-yellow-200"
            >Support</span
          >
          <h2 class="text-3xl sm:text-4xl font-semibold mb-10 sm:mb-6 dark:text-gray-200">
            Frequently asked questions
          </h2>

          <ul class="shadow-box">
            <BaseAccordion
              v-for="(accordion, index) in accordions"
              :key="index"
              :accordion="accordion"
            />
          </ul>
        </div>
      </BaseSection>
    </section>

    <section>
      <div class="mx-auto max-w-screen-xl px-4 py-16 sm:px-6 lg:px-8">
        <FooterBanner />
      </div>
    </section>
  </div>
</template>

<script setup>
import { ref } from "vue";
import Spotlight from '../components/Spotlight.vue'
import SpotlightCard from '../components/SpotlightCard.vue'
import Card01 from '../assets/images/logo/footer.png'
import Card02 from '../assets/images/logo/footer.png'
import Card03 from '../assets/images/logo/footer.png'

import TestimonialImg01 from "@/assets/images/logo/footer.png"
import TestimonialImg02 from "@/assets/images/logo/footer.png"
import TestimonialImg03 from "@/assets/images/logo/footer.png"
import FancyTestimonialsSlider from "@/components/FancyTestimonialsSlider.vue"

const testimonials = [
  {
    img: TestimonialImg01,
    quote: "The ability to capture responses is a game-changer. If a user gets tired of the sign up and leaves, that data is still persisted. Additionally, it's great to be able to select between formats.ture responses is a game-changer.",
    name: 'Jessie J',
    role: 'Ltd Head of Product'
  },
  {
    img: TestimonialImg02,
    quote: "I have been using this product for a few weeks now and I am blown away by the results. My skin looks visibly brighter and smoother, and I have received so many compliments on my complexion.",
    name: 'Mark Luk',
    role: 'Spark Founder & CEO'
  },
  {
    img: TestimonialImg03,
    quote: "As a busy professional, I don't have a lot of time to devote to working out. But with this fitness program, I have seen amazing results in just a few short weeks. The workouts are efficient and effective.",
    name: 'Jeff Kahl',
    role: 'Appy Product Lead'
  }
]
</script>

<script>
// import aosMixin from '@/mixins/aos'
export default {
  name: "IndexPage",
  data() {
    return {
      selected: 0,
      dropdownConcurency: false,
      dropdownCrypto: false,
      currencySelected: {
        img: "country-icon/eng.png",
        name: "USD",
      },
      currencies: [
        {
          img: "country-icon/eng.png",
          name: "USD",
        },
      ],
      cryptoSelected: {
        img: "crypto-icon/bitcoin.png",
        name: "BTC",
      },
      cryptocurrencies: [
        {
          img: "crypto-icon/bitcoin.png",
          name: "BTC",
        },
      ],
      trendings: [
        {
          id: 1,
          name: "Bitcoin",
          price: 43180.13,
          logo: "bitcoin.png",
          increase: true,
          data: [40, 35, 60, 75, 60, 75, 50],
        },
        {
          id: 2,
          name: "Ethereum",
          price: 3480.65,
          logo: "ethereum.png",
          increase: false,
          data: [25, 30, 60, 50, 80, 55, 80],
        },
        {
          id: 3,
          name: "Solana",
          price: 150.2,
          logo: "solana.png",
          increase: true,
          data: [40, 45, 40, 80, 50, 60, 35],
        },
        {
          id: 4,
          name: "Dogecoin",
          price: 0.1572,
          logo: "dogecoin.png",
          increase: true,
          data: [35, 70, 60, 80, 50, 60, 40],
        },
      ],
      topGainers: [
        {
          id: 1,
          name: "PAPPAY",
          price: 0.00374,
          logo: "pappay.png",
          increase: true,
          data: [30, 50, 45, 60, 70, 40, 45],
        },
        {
          id: 2,
          name: "Bitcoin Asia",
          price: 0.02096,
          logo: "bitcoin-asia.png",
          increase: true,
          data: [25, 60, 50, 60, 35, 50, 70],
        },
        {
          id: 3,
          name: "MoonRock",
          price: 0.004907,
          logo: "moonrock.png",
          increase: true,
          data: [40, 35, 40, 25, 50, 70, 45],
        },
        {
          id: 4,
          name: "NinjaFloki",
          price: 0.000123,
          logo: "ninjafloki.png",
          increase: true,
          data: [45, 35, 40, 30, 25, 45, 35],
        },
      ],
      recents: [
        {
          id: 1,
          name: "MetaCraft",
          price: 0.0608,
          logo: "metacraft.png",
          increase: false,
          data: [40, 50, 45, 60, 35, 40, 45],
        },
        {
          id: 2,
          name: "Frog",
          price: 0.5875,
          logo: "frog.png",
          increase: false,
          data: [25, 50, 45, 48, 40, 60, 45],
        },
        {
          id: 3,
          name: "Musk Doge",
          price: 0.04041,
          logo: "musk-doge.png",
          increase: true,
          data: [25, 35, 60, 45, 50, 45, 45],
        },
        {
          id: 4,
          name: "2SHARE",
          price: 1366.24,
          logo: "2share.png",
          increase: true,
          data: [35, 30, 60, 50, 35, 45, 40],
        },
      ],
      accordions: [
        {
          title: "Why should I choose NEFA?",
          description:
            "We're industry pioneers, having been in the cryptocurrency industry since 2016. We've facilitated more than 21 billion USD worth of transactions on our exchange for customers in over 40 countries. Today, we're trusted by over 8 million customers around the world and have received praise for our easy-to-use app, secure wallet, and range of features.",
        },
        {
          title: "How secure is NEFA?",
          description:
            "We're industry pioneers, having been in the cryptocurrency industry since 2016. We've facilitated more than 21 billion USD worth of transactions on our exchange for customers in over 40 countries. Today, we're trusted by over million customers around the world and have received praise for our easy-to-use app, secure wallet, and range of features.",
        },
        {
          title: "Do I have to buy a whole Bitcoin?",
          description:
            "We're industry pioneers, having been in the cryptocurrency industry since 2016. We've facilitated more than 21 billion USD worth of transactions on our exchange for customers in over 40 countries. Today, we're trusted by over million customers around the world and have received praise for our easy-to-use app, secure wallet, and range of features.",
        },
        {
          title: "How do I actually buy Bitcoin?",
          description:
            "We're industry pioneers, having been in the cryptocurrency industry since 2016. We've facilitated more than 21 billion USD worth of transactions on our exchange for customers in over 40 countries. Today, we're trusted by over million customers around the world and have received praise for our easy-to-use app, secure wallet, and range of features.",
        },
      ],
      steps: [
        {
          img: "sign-up.png",
          title: "Sign Up",
          description:
            "Sign up for your free NEFA Wallet on web, iOS or Android and follow our easy process to set up your profile",
        },
        {
          img: "fund.png",
          title: "Fund",
          description:
            "Choose your preferred payment method such as bank transfer or credit card to top up your NEFA Wallet",
        },
        {
          img: "buy-crypto.png",
          title: "Buy Crypto",
          description:
            "Buy Bitcoin or Ethereum, then securely store it in your Wallet or send it on easily to your friends anywhere",
        },
      ],
    };
  },
};
</script>
