<template>
  <ContentDoc path="/" />
</template>
<script setup lang="ts">

// Compare this snippet from pages\[...slug].vueconst { data } = await useAsyncData('home', () => queryContent('/').findOne())
</script>
