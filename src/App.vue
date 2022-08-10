<template>
  <div><HomeView /></div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import HomeView from './views/HomeView.vue'

export default defineComponent({
  components: {
    HomeView
  },
  setup() {
    return {}
  }
})
</script>

<style scoped></style>
