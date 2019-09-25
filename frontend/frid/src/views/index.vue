<template>
  <div class="index">
    <header>
      <img class="logo" src="../assets/logo.png" />
      <div class="frid-nav">
        <el-menu mode="horizontal">
          <el-menu-item @click="hoge" index="1">About</el-menu-item>
          <el-menu-item index="2">Features</el-menu-item>
          <el-menu-item index="3">
            <a href="#/signin">Get Started</a>
          </el-menu-item>
          <el-menu-item index="4">
            <a href="https://github.com/frid-smartware/frid" target="_blank">GitHub</a>
          </el-menu-item>
        </el-menu>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: "index",

  data() {
    return {};
  },
  methods: {
    hoge() {
      alert("hoge");
    }
  }
};
</script>

<style scoped>
.logo {
  display: inline-flex;
  max-width: 140px;
}

.frid-nav {
  width: 500px;
  margin-top: 1vh;
  margin-right: -60px;
  float: right;
}

a {
  text-decoration: none;
}
</style>
