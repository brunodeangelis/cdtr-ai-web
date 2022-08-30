<script setup>
useHead({
  title: "CONDUCTR.AI - Attractions Intelligence",
  htmlAttrs: {
    lang: "en",
  },
  meta: [
    {
      name: "robots",
      content: "noindex",
    },
  ],
});
</script>

<template>
  <main class="w-full h-screen relative">
    <img
      src="/conductrai.jpg"
      alt="CONDUCTR.AI teaser image"
      class="w-full h-full object-cover"
    />
    <footer
      class="px-8 w-full absolute left-1/2 bottom-[10%] sm:bottom-[15%] -translate-x-1/2 flex flex-col items-center gap-y-8"
    >
      <a href="https://conductr.co.uk" target="_blank">
        <CDTRAILogo class="w-[500px] max-w-full" />
      </a>
      <div class="flex flex-col items-center gap-y-3 gap-x-8 sm:flex-row">
        <a href="https://bit.ly/3ea0iUU" target="_blank" class="btn"
          >Watch the Launch</a
        >
        <a
          href="https://conductr.co.uk/latest/introducing-attractions-intelligence"
          target="_blank"
          class="btn"
          >Learn More</a
        >
      </div>
    </footer>
  </main>
</template>

<style>
body {
  @apply text-white md:text-lg;
}

.btn {
  @apply inline-flex text-center uppercase tracking-wider bg-dark px-6 py-3 ring-1 ring-white transition-all duration-200 ease-out hover:ring-primary hover:text-primary;
}
</style>
