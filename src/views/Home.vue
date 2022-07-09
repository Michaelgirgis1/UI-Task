<template>
  <div class="line-chart container">
    <h1 class="text-center">ui task</h1>
  </div>
</template>
<script>
// @ is an alias to /src
import Vue from "vue";
import vSelect from "vue-select";
Vue.component("v-select", vSelect);
import "vue-select/dist/vue-select.css";

import "simple-scrollbar/simple-scrollbar.css";

export default {
  name: "Home",
  components: {
  },
  data() {
    return {
      value: null,
      dimensionSelected: "Product",
      measureSelected: 'Cost'
    };
  },
  methods: {},
  mounted() {},
};
</script>
<style lang="scss">
.ss-scroll {
  background-color: red;
  opacity: 1;
}

// .multiselect__content-wrapper {
//   height: 200px;
// }

.test .vs__dropdown-menu {
  //ul
  height: 200px;
  overflow: hidden;
}
.line-chart {
  padding: 40px 0;
}

</style>
