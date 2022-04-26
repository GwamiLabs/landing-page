<template>
  <CardOne/>
  <CardTwo/>
  <CardThree/>
  <CardFour/>
  <CardFive/>
</template>

<script>
import CardOne from './components/CardOne.vue'
import CardTwo from './components/CardTwo.vue'
import CardThree from './components/CardThree.vue'
import CardFour from './components/CardFour.vue'
import CardFive from './components/CardFive.vue'

export default {
  name: 'App',
  components: {
    CardOne,
    CardTwo,
    CardThree,
    CardFour,
    CardFive,
}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
