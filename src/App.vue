<template>
  <v-app>
    <v-main>
      <div class="text-center">
        <router-link :to="{ name: 'HomeView' }">Home</router-link> |
        <router-link :to="{ name: 'AboutView' }">About</router-link>
      </div>
      <router-view />
    </v-main>
  </v-app>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'App',

  data() {
    return {
      //
    }
  }
})
</script>
