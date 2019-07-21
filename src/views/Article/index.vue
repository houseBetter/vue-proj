<template>
  <el-container>
    <el-header>
      <h1>{{title}}</h1>
      <el-divider></el-divider>
    </el-header>
    <el-main>
      {{content}}
    </el-main>
  </el-container>
</template>
<script>
export default {
  name: 'Article',
  props: ['title', 'content'],
  // data: function() {
  //   return {
  //     title: 'Hello Vue'
  //   }
  // }
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
.flutter {
  display: flex;
  align-items: center;
}
.flutter-icon {
  height: 20px;
}
.icon-large {
  font-size: 25px;
}
</style>


