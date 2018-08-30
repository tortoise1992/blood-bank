<template>
  <div>
    <div class="logo">
      测试工作台
    </div>
    <el-menu
      default-active="2"
      class="el-menu-vertical-demo"
      background-color="#001529"
      text-color="#fff"
      active-text-color="#1890ff">
      <el-submenu index="1">
        <template slot="title">
          <i class="el-icon-location"></i>
          <span>导航一</span>
        </template>

        <el-menu-item index="1-4-1">选项1</el-menu-item>
      </el-submenu>
      <el-menu-item index="2">
        <i class="el-icon-menu"></i>
        <span slot="title">导航二</span>
      </el-menu-item>
      <el-menu-item index="4">
        <i class="el-icon-setting"></i>
        <span slot="title">导航四</span>
      </el-menu-item>
    </el-menu>
  </div>
</template>

<script>
export default {

};
</script>

<style scoped>
.el-menu{
  border: none;
}
.logo{
  height: 60px;
  line-height: 60px;
  text-align: center;
  background-color: #002140;
  color: #fff;
}
</style>
