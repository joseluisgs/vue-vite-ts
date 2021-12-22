<template>
  <div class="home container mx-auto px-4">
    <div class="h-60 mb-8 flex justify-center">
      <transition name="fade">
        <img
          alt="Vue logo"
          src="../assets/images/logo.png"
        >
      </transition>
    </div>
    <HelloWorld msg="Welcome to Your Vue.js Vite TS App" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import HelloWorld from '../components/HelloWorld.vue'

export default defineComponent({
  name: 'Home',
  components: {
    HelloWorld
  }
})
</script>

<style scoped>
.fade-enter-active {
  transition: opacity 1s ease-in-out;
}
.fade-enter-to {
  opacity: 1;
}
.fade-enter {
  opacity: 0;
}
</style>
