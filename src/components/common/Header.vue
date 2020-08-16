<template>
  <el-container>
    <el-header class="header" height="100px">
      <h3>测试网站</h3>
    </el-header>
    <el-main>
      <router-view/>
    </el-main>
  </el-container>
</template>

<style>
  .header{
    background-color: #409EFF;
    color: white;
  }
</style>