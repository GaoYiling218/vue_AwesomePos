<template>
  <div id="app">
    <leftNav></leftNav>
    <div class="main">
      <Pos></Pos>
      <!-- <router-view></router-view> -->
    </div>
  </div>
</template>

<script>
import leftNav from "@/components/common/leftNav";
import Pos from "@/components/pages/Pos";

export default {
  name: "app",
  components: {
    leftNav,
    Pos
  }
};
</script>

<style>
#app {
  font-family: "Microsoft YaHei", "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
  height: 100%;
}

.main {
  float: left;
  width: 95%;
  background-color: #eff2f7;
  height: 100%;
  overflow: auto;
}
</style>
