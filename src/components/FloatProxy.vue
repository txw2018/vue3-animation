<script setup lang="ts">
import { metaData } from '../composables/floating'
const props = defineProps<{
  modelValue?: string
}>()
const attrs = useAttrs()

metaData.attrs = attrs
metaData.props = props

</script>
<template>
  <slot />
</template>
