<template>
  <main font-sans p="x-4 y-10" text="center gray-700 dark:gray-200">
    <router-view />
  </main>
  <FloatContainer v-slot="slotProps">
    <TheImage v-bind="{...slotProps}" />
  </FloatContainer>
</template>
