<template>
  <NavBar />
  <IntroPage />
  <OurProducts />
  <OurTeam />
  <OurPartners />
  <KlimaEcosystem />
</template>

<script>
import NavBar from "./components/NavBar.vue";
import IntroPage from "./components/IntroPage.vue";
import OurProducts from "./components/OurProducts.vue";
import OurTeam from "./components/OurTeam.vue";
import OurPartners from "./components/OurPartners.vue";
import KlimaEcosystem from "./components/KlimaEcosystem.vue";

export default {
  name: "App",
  components: {
    NavBar,
    IntroPage,
    OurProducts,
    OurTeam,
    OurPartners,
    KlimaEcosystem,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
body {
  height: 100%;
  background-image: linear-gradient(
    #c2cab5 0%,
    #c2cab5 22%,
    #3a4c17 22%,
    #3a4c17 45.2%,
    #caccc6 45.2%,
    #caccc6 66%,
    #c2cab5 66%,
    #c2cab5 77.3%,
    #caccc6 77.3%,
    #caccc6 100%
  );
}
</style>
