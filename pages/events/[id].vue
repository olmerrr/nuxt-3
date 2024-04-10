<template>
  event id: {{ $route.params.id }};
</template>

<script setup>
  const nuxt = useNuxtApp();
  console.log(nuxt);

  const route = useRoute();
</script>
