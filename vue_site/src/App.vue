<template>
  <div id="app">
    <el-row :gutter="20">
      <TheHeader></TheHeader>
    </el-row>

    <el-row :gutter="20">
      <router-view></router-view>
    </el-row>

    <el-row :gutter="20">
      <TheFooter></TheFooter>
    </el-row>
  </div>
</template>

<script>
import TheHeader from "./components/layouts/TheHeader";
import TheFooter from "./components/layouts/TheFooter";

export default {
  name: "App",
  components: {
    TheHeader,
    TheFooter
  }
 
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;  
}
</style>
