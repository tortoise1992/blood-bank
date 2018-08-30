<template>
  <div>
    <el-breadcrumb separator-class="el-icon-arrow-right">
      <el-breadcrumb-item :to="{ path: '/' }">首页</el-breadcrumb-item>
      <el-breadcrumb-item>活动管理</el-breadcrumb-item>
      <el-breadcrumb-item>活动列表</el-breadcrumb-item>
      <el-breadcrumb-item>活动详情</el-breadcrumb-item>
    </el-breadcrumb>
  </div>
</template>

<script>
  export default {

  }
</script>

<style scoped>
.el-breadcrumb{
  height: 54px;
  line-height: 54px;
  background-color: #fff;
  box-shadow: 0 -1px 4px rgba(0,21,41,.08);
  border-bottom: 1px solid #e8e8e8;
  padding: 0 32px;
  box-sizing: border-box;
}
</style>
