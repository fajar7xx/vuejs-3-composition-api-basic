<script setup>
  import {ref} from 'vue'
  const message = ref("halo dari vuejs 3")

  setTimeout(() => {
    console.log(message)
    message.value = "saya fajar siagian"
  }, 5000);
</script>

<template>
  <div>{{message}}</div>
</template>

<style lang="css" scoped>
</style>
