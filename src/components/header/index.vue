<template>
  <div>
    欢迎您，
    <el-dropdown trigger="click">
      <span class="el-dropdown-link">
        阿晖<i class="el-icon-arrow-down el-icon--right"></i>
      </span>
      <el-dropdown-menu slot="dropdown">
        <el-dropdown-item>个人中心</el-dropdown-item>
        <el-dropdown-item>修改密码</el-dropdown-item>
        <el-dropdown-item>设置</el-dropdown-item>
        <el-dropdown-item>退出</el-dropdown-item>
      </el-dropdown-menu>
    </el-dropdown>
  </div>
</template>

<script>
  export default {

  }
</script>

<style scoped>
.el-dropdown{
  margin-right: 30px;
}
.el-dropdown-link{
  cursor: pointer;
  outline: none;
}
</style>
