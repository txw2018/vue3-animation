<script setup lang="ts">
import { metaData } from '../composables/floating'
</script>
<template>
  <div>
    <slot v-bind="{...metaData.attrs}" />
  </div>
</template>
