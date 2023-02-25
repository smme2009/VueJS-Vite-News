<script setup>
import LayoutHeader from './components/Header.vue'
</script>

<template>
  <div class="common-layout">
    <el-container>
      <el-header height="150px">
        <LayoutHeader />
      </el-header>
      <el-container>
        <el-main></el-main>
        <el-aside width="300px"></el-aside>
      </el-container>
    </el-container>
  </div>
</template>

<style>
.el-header {
  background-color: #001F3F;
}

.el-container {
  background-color: #AAAAAA
}
</style>