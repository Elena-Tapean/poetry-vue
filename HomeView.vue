<template>
  <div class="home">
    <img alt="logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to My Poetry Vue Blog!"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>

<style scoped lang="scss">
img {
  height: 150px;
}
</style>

