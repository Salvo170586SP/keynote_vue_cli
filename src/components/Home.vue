<template>
  <div>
    <Header />
    <Jumbotron />
    <WhoWeAre />
    <Subscribe />
    <Speackers />
    <Program />
    <Map />
  </div>
</template>

<script >
import Header from "./Header.vue";
import Jumbotron from "./Jumbotron.vue";
import WhoWeAre from "./WhoWeAre.vue";
import Subscribe from "./Subscribe.vue";
import Speackers from "./Speackers.vue";
import Program from "./Program.vue";
import Map from "./Map.vue";
export default {
  name: "Home",
  components: {
    Header,
    Jumbotron,
    WhoWeAre,
    Subscribe,
    Speackers,
    Program,
    Map
},
};
</script>

<style lang="scss">
</style>