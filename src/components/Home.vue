<template>
  <div>
    <Header />
    <Jumbotron />
    <WhoWeAre />
  </div>
</template>

<script >
import Header from "./Header.vue";
import Jumbotron from "./Jumbotron.vue";
import WhoWeAre from "./WhoWeAre.vue";
export default {
  name: "Home",
  components: {
    Header,
    Jumbotron,
    WhoWeAre
  },
};
</script>

<style lang="scss">
</style>