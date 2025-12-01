<template>
  <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
  <BaseCard></BaseCard>
</template>

<script>
import BaseCard from './components/BaseCard.vue'

export default {
  name: 'App',
  components: {
    BaseCard
  }
}
</script>

<style>
body{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  background: radial-gradient(71.11% 100% at 50% 0%, #020204 14.6%, #011F35 100%);
}

#app {
  width: 100vw;
  min-height: 100vh;
}
</style>
