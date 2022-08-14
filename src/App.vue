<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <div class="common-layout">
    <el-container>
      <el-header>
        <el-menu mode="horizontal">
          <el-menu-item index="1">
            Home
          </el-menu-item>
        </el-menu>
      </el-header>
      <el-main>
        <RouterView />
      </el-main>
    </el-container>
  </div>
</template>

<style scoped>
.el-header {
  /* background-color: Pink; */
}
</style>
