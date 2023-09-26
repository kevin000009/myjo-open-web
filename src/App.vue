<script setup lang="ts">
import 'element-plus/theme-chalk/dark/css-vars.css'
import './styles/dark/css-vars.css'
</script>

<template>
  <header>
    <!--    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125"/>-->
    <title>MYJO-OPEN-API</title>
  </header>
  <body>
    <div id="app">
      <template>
        <div class="common-layout">
          <el-container>
            <el-header>Header</el-header>
            <el-container>
              <el-aside width="200px">Aside</el-aside>
              <el-main>Main</el-main>
            </el-container>
          </el-container>
        </div>
      </template>
    </div>
  </body>
  <!--  <RouterView/>-->
</template>

