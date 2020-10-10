<template>
  <div id="nav">
    <router-view></router-view>
    <tab-bar></tab-bar>
  </div>
</template>
<script>
import TabBar from "./components/tabbar/Index";
export default {
  name: "Home",
  components: {
    TabBar
  }
};
</script>
<style lang="scss" scoped>
@import url(./assets/css/base.css);
</style>
