<template>
  <div>
    <router-link :to="{ name: 'HomeView' }">Home</router-link> |
    <router-link :to="{ name: 'AboutView' }">About</router-link>
  </div>
  <div><router-view></router-view></div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  setup() {
    return {}
  }
})
</script>

<style scoped></style>
