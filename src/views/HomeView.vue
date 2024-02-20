<template>
  <div class="home">
    <h1>Hello, This is Home Page.</h1>
    <RouterLink to="/">Home</RouterLink> |
    <RouterLink to="/about">About</RouterLink>
    <hr>
    <HelloWorld />
    <hr>
    <div>
      <h4>TEST</h4>
    </div>
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  components: {
    HelloWorld
  }
}
</script>

<style scoped>
</style>
