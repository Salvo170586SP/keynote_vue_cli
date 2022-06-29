<template>
  <div>
    <Header />
    <Jumbotron />
    <WhoWeAre />
    <Subscribe />
    <Speackers />
  </div>
</template>

<script >
import Header from "./Header.vue";
import Jumbotron from "./Jumbotron.vue";
import WhoWeAre from "./WhoWeAre.vue";
import Subscribe from "./Subscribe.vue";
import Speackers from "./Speackers.vue";
export default {
  name: "Home",
  components: {
    Header,
    Jumbotron,
    WhoWeAre,
    Subscribe,
    Speackers
  },
};
</script>

<style lang="scss">
</style>