<script setup lang="ts">
const a = $ref(false)

</script>
<template>
  <div overflow-hidden transition-all @click="a=!a">
    <img v-if="a" src="https://images.unsplash.com/photo-1649960861739-113b8588eaf8?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHwzMHx8fGVufDB8fHx8&auto=format&fit=crop&w=800&q=60" alt="">
    <img v-else src="https://images.unsplash.com/photo-1649856018930-cb8bed61f48f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHwzNXx8fGVufDB8fHx8&auto=format&fit=crop&w=800&q=60">
  </div>
</template>
<style scope lang="scss"></style>
