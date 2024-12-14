<script lang="ts" setup>
  const route = useRoute()
  console.log(route.params.slug)
</script>

<template>
  <div>
    <h1>Category Slug Page</h1>
    <h2 v-if="$route.params.slug">
      Category: {{ $route.params.slug }}
    </h2>
  </div>
</template>

<style scoped></style>
