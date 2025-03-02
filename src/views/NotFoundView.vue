<script setup lang='ts'>
import { useRoute } from 'vue-router';

const route = useRoute();

</script>

<template>
  <div>{{ route.params.catchAll }}</div>
</template>

<style lang='scss' scoped>
</style>
