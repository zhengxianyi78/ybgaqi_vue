<template>
  <el-row :gutter="20">
    <el-col :span="15" :offset="1">
      <el-container direction="vertical">
        <HomeTop></HomeTop>
      </el-container>

      <el-container direction="vertical">
        <HomeMain></HomeMain>
      </el-container>

      <el-container direction="vertical">
        <HomeDown></HomeDown>
      </el-container>
    </el-col>

    <el-col :span="7" >
        <HomeSidebar></HomeSidebar>
    </el-col>
    <el-col :span="1">
    </el-col>
  </el-row>
</template>

<script>
import HomeTop from "../views/Homes/HomeTop";
import HomeMain from "../views/Homes/HomeMain";
import HomeSidebar from "../views/Homes/HomeSidebar";
import HomeDown from "../views/Homes/HomeDown";

export default {
  name: "Home",

  components: {
    HomeMain: HomeMain,
    HomeTop: HomeTop,
    HomeDown: HomeDown,
    HomeSidebar: HomeSidebar
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

.card-top {
  margin-top: 30px;
  padding: 10px;
  text-align: left;
}
.text-r{
  text-align:right;
}
.text-l{
  text-align: left;
}
</style>
