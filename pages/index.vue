<script setup>
const { $sayHello } = useNuxtApp()
console.log(useNuxtApp());
$sayHello('Jobu')
</script>

<template>
  <div>
    <!-- <Alert />
    <Profile /> -->
    Main Page
    <!-- <IconBell /> -->
    <!-- <img src="/image.png" alt="" /> -->
  </div>
</template>