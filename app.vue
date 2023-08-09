<template>
  <ContentDoc path="/" />
</template>
<script setup lang="ts">

// Compare this snippet from pages\[...slug].vue:
const { data } = await useAsyncData('home', () => queryContent('/').findOne())
</script>
