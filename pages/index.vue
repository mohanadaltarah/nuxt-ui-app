<script lang="ts" setup>
const loading = true;
</script>

<template>
  <UContainer>
    <h1 class="text-2xl">This is a button</h1>
    <UButton :ui="{strategy:'override', rounded: 'rounded-full'}" color="scarlet"
             size="xs" to="/about"
    >click me
    </UButton>
  </UContainer>
</template>

<style scoped>

</style>