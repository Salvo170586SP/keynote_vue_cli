<template>
  <div>
    <Header />
    <Jumbotron />
    <WhoWeAre />
    <Subscribe />
    <Speackers />
    <Program />
    <Map />
    <Location />
    <RecentNews />
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
import Location from "./Location.vue";
import RecentNews from "./RecentNews.vue";
export default {
  name: "Home",
  components: {
    Header,
    Jumbotron,
    WhoWeAre,
    Subscribe,
    Speackers,
    Program,
    Map,
    Location,
    RecentNews
},
};
</script>

<style lang="scss">
</style>