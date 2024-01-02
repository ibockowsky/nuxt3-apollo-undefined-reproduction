<template>
  <div>
    <NuxtWelcome />
  </div>
</template>

<script setup lang="ts">
const nuxtApp = useNuxtApp();

const { $apollo } = nuxtApp;
</script>
