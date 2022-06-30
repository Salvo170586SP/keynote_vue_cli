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
    <Tikets />
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
import Tikets from "./Tikets.vue";
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
    RecentNews,
    Tikets
},
};
</script>

<style lang="scss">
</style>