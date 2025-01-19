<script setup>
const nuxtApp = useNuxtApp()


console.log(nuxtApp)
</script>
<template>
  <div>
    event id: {{ $route.params.id }}
  </div>
</template>