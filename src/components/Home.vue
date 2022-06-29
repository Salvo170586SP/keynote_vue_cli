<template>
  <div>
    <Header />
    <Jumbotron />
  </div>
</template>

<script >
import Header from "./Header.vue";
import Jumbotron from "./Jumbotron.vue";
export default {
  name: "Home",
  components: {
    Header,
    Jumbotron
  },
};
</script>

<style lang="scss">
</style>