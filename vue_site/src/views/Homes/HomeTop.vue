
 <template>
  <el-card>
    <el-row>
      <el-col :span="15">
        <el-carousel trigger="click" size="mini">
          <el-carousel-item v-for="item in 4" :key="item">
            <el-image :src="src"></el-image>
          </el-carousel-item>
        </el-carousel>
      </el-col>

      <el-col :span="9">
        <el-card shadow="never">
          <div slot="header" class="text">
            <el-link :underline="false">无下划线</el-link>
          </div>
          <p class="text">埃里克涉及到四点放假啊多少积分按时灯笼裤飞机阿</p>
        </el-card>
      </el-col>
    </el-row>
  </el-card>
</template>


<script>
export default {
  data() {
    return {
      src: "https://cube.elemecdn.com/6/94/4d3ea53c084bad6931a56d5158a48jpeg.jpeg"
    };
  }
};
</script>

  <style>
.text {
  font-size: 14px;
  text-align: right;
}
</style>