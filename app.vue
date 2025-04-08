<script setup>
useHead({
  htmlAttrs: { lang: "en-US" },
  title: "Philip Jensen",
  meta: [
    {
      name: "description",
      content:
        "Site to test and show of my dev skills",
    },
  ],
  bodyAttrs: {
    class: 'font-display'
  }
});
</script>

<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>
