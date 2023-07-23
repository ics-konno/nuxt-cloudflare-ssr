<script lang="ts" setup>
const { data } = useFetch("/api/hello");
</script>

<template>
  <div>
    <NuxtWelcome />
    {{ data }}
  </div>
</template>
