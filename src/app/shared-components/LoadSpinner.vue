<template>
  <div v-if="isLoading" class="spinner">
    <q-spinner/>
  </div>
</template>

<script>
  export default {
    props: ['isLoading']
  }
</script>

<style>
</style>
