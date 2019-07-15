<template>
  <el-header>
    <el-row type="flex" justify="center">
      <el-col :span="3">
        <el-link>
          <img src="https://b-gold-cdn.xitu.io/v3/static/img/logo.a7995ad.svg" alt="掘金" />
        </el-link>
      </el-col>
      <el-col :span="6">
        <el-menu mode="horizontal">
          <el-menu-item index="1">首页</el-menu-item>
          <el-menu-item index="2">沸点</el-menu-item>
          <el-menu-item index="3">话题</el-menu-item>
          <el-menu-item index="4">小册</el-menu-item>
          <el-menu-item index="5">活动</el-menu-item>
        </el-menu>
      </el-col>
      
      <el-col :span="2">
        <div>
          <img class="flutter-icon" src="https://b-gold-cdn.xitu.io/v3/static/img/flutter-xiaoce.f59b99e.png">
          <span style="margin-left: 10px;">Flutter</span>
        </div>
        
      </el-col>
      <el-col :span="3">
        <el-input
          placeholder="请输入内容"
          prefix-icon="el-icon-search"
        >
        </el-input>
        
      </el-col>
      <el-col :span="3">
        <el-button type="primary">
          写文章
        </el-button>
      </el-col>
      <el-col :span="2"><i class="el-icon-message-solid"></i></el-col>
      <el-col :span="2">
        <el-avatar size="large" src="http://cube.elemecdn.com/3/7c/3ea6beec64369c2642b92c6726f1epng.png"></el-avatar>
      </el-col>
    </el-row>
  </el-header>
</template>
<script>
export default {
  name: 'Header'
}
</script>
<style scoped>
.el-header {
  width: 100%;
}
.el-menu.el-menu--horizontal {
  border-bottom-color: #ffffff;
}
.el-col {
  display: flex;
  align-items: center;
}
.flutter-icon {
  height: 20px;
}
</style>


