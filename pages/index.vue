<script setup lang="ts">
const route = useRoute()
</script>

<template>
  <h1>
    Page: 首頁
  </h1>
  <p>
    目前路由的路徑 - route.fullpath 為 : {{ route.fullPath }}
  </p>
</template>

<style scoped></style>
