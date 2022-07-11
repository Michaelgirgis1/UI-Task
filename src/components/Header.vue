<template>
  <div class="container">
     <header class="header" id="header">
      <div class="bell">
        <img src="./../assets/alert.png" alt="alert image " srcset="">

      </div>
      <div class="logo">
        <img src="./../assets/logo.png" alt="logo image" srcset="">

      </div>
      <div class="menu">
        <img src="./../assets/menu.png" alt="menu image" srcset="">

      </div>

     </header>
  </div>
</template>
<script>
export default {
  name: "Header",
  data() {
    return {};
  },
  methods: {},

  mounted() {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.header {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
</style>
