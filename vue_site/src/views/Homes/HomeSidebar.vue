<template>
  <el-container>
    <el-main>
      <el-card>
        <div class="demo-input-suffix">
          <el-input placeholder="请输入内容" prefix-icon="el-icon-search" v-model="input2"></el-input>
        </div>
      </el-card>
      <!-- 关键词热度 -->
      <Tagkeys></Tagkeys>

      <el-card class="card-top">
        <!-- 有效资源 -->

        <LinksUrl></LinksUrl>
      </el-card>
    </el-main>
  </el-container>
</template>
<script>
import Tagkeys from "../Tagkeys/Tagkeys";
import LinksUrl from "../Topics/LinksUrl";

export default {
  name: "HomeSidebar",

  data() {
    return {
      input2: ""
    };
  },

  components: {
    Tagkeys: Tagkeys,
    LinksUrl: LinksUrl
  }
};
</script>