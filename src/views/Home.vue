<template>
  <div class="home">
    <Header />
    <Banner />
    <HotGames />
    <div class="home__list">
      <ListMenu />
      <ListItems />
    </div>
  </div>
</template>
<script>
import Header from './../components/Header.vue'
import Banner from './../components/Banner.vue'
import HotGames from './../components/HotGames.vue'
import ListMenu from './../components/ListMenu.vue'
import ListItems from './../components/ListItems.vue'

export default {
  name: "Home",
  components: {
    Header,
    Banner,
    HotGames,
    ListMenu,
    ListItems
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
