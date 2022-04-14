<script setup lang="ts">

const router = useRouter()
const go = () => {
  router.push('/foo')
}
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
  </div>
</template>
