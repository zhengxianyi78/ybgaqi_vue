<template>
  <div class="navbar-static-top">
    <el-container direction="vertical" style="text-align: center">
      <span>
      
      </span>
    </el-container>
    <el-container direction="vertical">

      <el-row :gutter="20">
        <el-col :span="3" :offset="1">
<img src="https://shadow.elemecdn.com/app/element/hamburger.9cf7b091-55e9-11e9-a976-7f4d0b07eef6.png" class="image" style="width: 280px; height: 60px"/>
        </el-col>
        <el-col :span="6">
          <el-avatar :size="50" class="txt-bg-color">文</el-avatar>
          <el-avatar :size="50" class="img-bg-color">图</el-avatar>
          <el-avatar :size="50" class="vod-bg-color">影</el-avatar>
        </el-col>
        <el-col :span="13">
          <p style="align:right" class="text-r">分享家乡文、图、影，回忆美好人生~</p>
          <el-divider content-position="right">YBGAQI</el-divider>
        </el-col>
        <el-col :span="2"></el-col>
      </el-row>
    </el-container>
  </div>
</template>


<script>
export default {};
</script>

<style>
.navbar-static-top {
  margin-bottom: 40px;
  margin-top: 60px;
  
}
.txt-bg-color {
  background: #000;
  color: #ffffff;
}
.img-bg-color {
  background: #409eff;
  color: #ffffff;
}
.vod-bg-color {
  background: #909399;
  color: #ffffff;
}
</style>