<template>
  <div class="index">
    
    <img class="logo" src="../assets/logo.png">
    <el-menu
      class="frid-nav"
      mode="horizontal"
    >
      <el-menu-item index="1">About</el-menu-item>
      <el-menu-item index="2">Features</el-menu-item>
      <el-menu-item index="3">
          <a href="#/signin">Get Started</a>
          </el-menu-item>
      <el-menu-item index="4">
        <a href="https://github.com/frid-smartware/frid" target="_blank">GitHub</a>
      </el-menu-item>
    </el-menu>
  </div>
</template>


<style scoped>

.logo{
    display: inline-flex;
    max-width: 120px;
}

/* .frid-nav{
} */

</style>
