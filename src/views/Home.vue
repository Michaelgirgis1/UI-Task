<template>
  <div class="home">
    <Header />
    <Banner />
    <HotGames />
    <DragonFestival />
    <ListItems />
  </div>
</template>
<script>
import Header from './../components/Header.vue'
import Banner from './../components/Banner.vue'
import HotGames from './../components/HotGames.vue'
import ListItems from './../components/ListItems.vue'
import DragonFestival from './../components/DragonFestival.vue'


export default {
  name: "Home",
  components: {
    Header,
    Banner,
    HotGames,
    ListItems,
    DragonFestival
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
