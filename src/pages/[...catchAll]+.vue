<script setup lang="ts">
import { useRoute } from 'vue-router'

const route = useRoute()
</script>

<template>
  <div>
    <h1>404 Not Found</h1>
    <div>{{ route.params?.catchAll }}</div>
  </div>
</template>

<style lang="scss" scoped></style>
