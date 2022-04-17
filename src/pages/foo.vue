<script setup lang="ts">
import FloatProxy from '../components/FloatProxy.vue'
</script>
<template>
  <div>
    <div>index</div>
    <div>
      <router-link
        class="m-3 text-sm btn"
        to="/"
      >
        Back
      </router-link>
    </div>
    <FloatProxy w-100 h-100 rounded="1/2" m10 />
  </div>
</template>
