<template>
<el-row>
  <el-col>
    <el-card>
      <img src="https://shadow.elemecdn.com/app/element/hamburger.9cf7b091-55e9-11e9-a976-7f4d0b07eef6.png" class="image">
      <div style="padding: 10px;">
        <span>好吃的汉堡</span>
        <div class="bottom clearfix">
          <time class="time">{{ currentDate }}</time>
          <el-button type="text" class="button">操作按钮</el-button>
        </div>
      </div>
    </el-card>
  </el-col>
</el-row>
</template>
<script>
    
export default {
    name: "LinksUrl",
  data() {
    return {
      currentDate: new Date()
    };
  }
}
</script>

  