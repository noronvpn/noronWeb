
<template>
  <nav class="p-6 lg:flex lg:justify-between lg:items-center" id="header">
    <div class="flex items-center justify-center">
      <h1>Noron</h1>
    </div>
    <button @click="toggleDarkMode">Toggle Dark Mode</button>
    <ThemeToggle/>
  </nav>
</template>
<script>
export default {
  methods: {
    handleScroll() {
      const header = document.getElementById("header");
      if (window.scrollY > 10) {
        header.classList.add("shadow-lg");
      } else {
        header.classList.remove("shadow-lg");
      }
    },
    toggleDarkMode() {
      if (localStorage.theme === 'dark') {
        localStorage.theme = 'light'
      } else {
        localStorage.theme = 'dark'
      }
      // Toggle the dark mode class on the HTML element
      document.documentElement.classList.toggle('dark')
    },
    beforeMount() {
      window.addEventListener("scroll", this.handleScroll);
    },
    beforeDestroy() {
      window.removeEventListener("scroll", this.handleScroll);
    },
  },
};
</script>

<style>
.stick {
  position: sticky;
}
</style>