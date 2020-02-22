<template>
    <el-card class="card-top">
   <div slot="header">
    <h5>关键词热度</h5>
  </div>
  <el-timeline>
    <el-timeline-item timestamp="2018/4/12" placement="top">
        
          <el-tag v-for="o in 10" :key="o" type="info" style="margin: 2px">标签三</el-tag>
        
    </el-timeline-item>
    <el-timeline-item timestamp="2018/4/3" placement="top">
         <el-tag v-for="o in 10" :key="o" type="info" style="margin: 2px">标签三</el-tag>
    </el-timeline-item>
    <el-timeline-item timestamp="2018/4/2" placement="top">
         <el-tag v-for="o in 10" :key="o" type="info" style="margin: 2px">标签三</el-tag>
    </el-timeline-item>
  </el-timeline>
</el-card>
</template>

<script>
export default {
    name: "Tagkeys",
}
</script>

<style scoped>
.el-card__body .el-timeline {
  padding: 0px;
}
</style>