<template>
  <el-container>
    <el-aside width="200px">
      <SideNav></SideNav>
    </el-aside>
    <el-container class="wrapper">
      <el-header class="header">
        <Vheader/>
      </el-header>
      <div class="content">
        <div class="main-wrapper">
          <Bread></Bread>
          <el-main>
            <!-- 第一层路由 -->
            <router-view>

            </router-view>
          </el-main>
        </div>
        <el-footer>
          <Vfooter/>
        </el-footer>
      </div>
    </el-container>
  </el-container>
</template>

<script>
import Vheader from '@/components/header'
import Vfooter from '@/components/footer'
import SideNav from '@/components/side-nav'
import Bread from '@/components/bread'
export default {
  name: 'App',
  components:{
    Vheader,
    Vfooter,
    SideNav,
    Bread
  }
}
</script>

<style>

</style>
