<template>
  <div id="app">
    <div class="tabBar">
      <TabBar></TabBar>
    </div>
  </div>
</template>

<script>
import TabBar from "./components/tabBar";

export default {
  name: "App",
  components: {
    TabBar,
  },
};
</script>

<style scoped>
 .tabBar {
  position: fixed;
  height: 49px;
  bottom: 0;
  left: 0;
  width: 100%;
 }
</style>
