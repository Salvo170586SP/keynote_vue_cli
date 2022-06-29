<template>
  <div>
    <Header />
    <Jumbotron />
    <WhoWeAre />
    <Subscribe />
  </div>
</template>

<script >
import Header from "./Header.vue";
import Jumbotron from "./Jumbotron.vue";
import WhoWeAre from "./WhoWeAre.vue";
import Subscribe from "./Subscribe.vue";
export default {
  name: "Home",
  components: {
    Header,
    Jumbotron,
    WhoWeAre,
    Subscribe,
  },
};
</script>

<style lang="scss">
</style>