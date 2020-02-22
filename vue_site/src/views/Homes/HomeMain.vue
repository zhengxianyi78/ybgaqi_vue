<template>
  <el-card class="card-top">
    <div>
      <span>
        <el-link :underline="false">
          无下
          <el-badge class="mark" :value="3" />
        </el-link>
      </span>
      <el-divider direction="vertical"></el-divider>
      <span>
        <el-link :underline="false">
          划线
          <el-badge class="mark" :value="3" />
        </el-link>
      </span>
      <el-divider direction="vertical"></el-divider>
      <span>
        <el-link :underline="false">
          无下划线
          <el-badge class="mark" :value="3" />
        </el-link>
      </span>
      <el-divider direction="vertical"></el-divider>
      <span>
        <el-badge :value="200" :max="99" class="item">
          <el-button size="mini">评论</el-button>
        </el-badge>
      </span>
    </div>
    <el-divider></el-divider>
    <div class="item">
      <h6>
        <el-avatar src="https://cube.elemecdn.com/0/88/03b0d39583f48206768a7534e55bcpng.png"></el-avatar>更新 Github 模板啊手啊手动阀手动阀十分啊动阀手动阀手动阀手动阀撒发射点发撒地方啊师傅
      </h6>
      <el-button style="float: right; padding: 3px 0" type="text">操作按钮</el-button>
      <p class="text-right">王小虎 提交于 2018/4/12 20:46</p>
    </div>
  </el-card>
</template>
<script>
export default {
  name: "HomeMain"
};
</script>

<style>
.item {
  margin: 10px;
  margin-right: 40px;
}
</style>