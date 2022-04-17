<script setup lang="ts">
import FloatProxy from '../components/FloatProxy.vue'
</script>

<template>
  <div>
    <div>index</div>
    <div>
      <router-link
        class="m-3 text-sm btn"
        to="/foo"
      >
        Go
      </router-link>
    </div>
    <FloatProxy w-50 h-50 rounded-1 />
  </div>
</template>
