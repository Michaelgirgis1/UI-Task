<template>
  <div class="home-page">
    <Header />
    <Banner />
    <HotGames />
  </div>
</template>
<script>
import Header from './../components/Header.vue'
import Banner from './../components/Banner.vue'
import HotGames from './../components/HotGames.vue'


export default {
  name: "Home",
  components: {
    Header,
    Banner,
    HotGames
  },
  data() {
    return {
    };
  },
  methods: {},
  mounted() {},
};
</script>
<style lang="scss">

</style>
