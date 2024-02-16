<script setup>
const route = useRoute().params;

</script>

<template>
<div>
  event id: {{ $route.params.id }}
</div>
</template>

<style scoped>

</style>