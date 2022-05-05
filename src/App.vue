<template>
  <NavBar />
  <IntroPage/>
  <OurProducts/>
  <OurTeam/>
  <OurPartners/>
  <KlimaEcosystem/>
  
</template>

<script>

import NavBar from "./components/NavBar.vue";
import IntroPage from './components/IntroPage.vue'
import OurProducts from './components/OurProducts.vue'
import OurTeam from './components/OurTeam.vue'
import OurPartners  from './components/OurPartners.vue'
import KlimaEcosystem from './components/KlimaEcosystem.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    IntroPage,
    OurProducts,
    OurTeam,
    OurPartners,
    KlimaEcosystem
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
