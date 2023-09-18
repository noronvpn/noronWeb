<template>
  <div
    class="grid h-screen px-4 bg-white place-content-center dark:bg-gray-900"
  >
    <h1 class="tracking-widest text-gray-500 uppercase dark:text-gray-400">
      <span>{{ error.statusCode }}</span> |
      <span>{{ error.statusMessage }}</span>
    </h1>
    <div class="flex justify-center items-center mt-10">
      <button
        class="group relative inline-flex items-center overflow-hidden rounded bg-indigo-600 px-8 py-3 text-white focus:outline-none focus:ring active:bg-indigo-500"
        @click="handleClearError"
      >
        <span class="absolute -end-full transition-all group-hover:end-4">
          <svg
            class="h-5 w-5 rtl:rotate-180"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M17 8l4 4m0 0l-4 4m4-4H3"
            />
          </svg>
        </span>

        <span class="text-sm font-medium transition-all group-hover:me-4">
          Home
        </span>
      </button>
    </div>
  </div>
</template>

<script setup>
defineProps(["error"]);
const handleClearError = () => clearError({ redirect: "/ " });
</script>

<style scoped></style>
