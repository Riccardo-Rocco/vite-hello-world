<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <img src="https://picsum.photos/seed/picsum/200" alt="">
</template>

<style scoped>
</style>
