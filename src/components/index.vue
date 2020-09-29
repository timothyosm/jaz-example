<template>
  <div>
    <el-menu
      id="menu"
      :default-active="activeIndex"
      class="el-menu-demo"
      mode="horizontal"
      @select="handleSelect"
    >
      <el-menu-item index="0"
        ><img src="..\assets\JAZ.png" alt="" style="width: 50%"
      /></el-menu-item>
      <el-menu-item index="1">How can we help?</el-menu-item>
      <el-submenu index="2">
        <template slot="title">About JAZ</template>
        <el-menu-item index="2-1">Our Story</el-menu-item>
        <el-menu-item index="2-2">Who Is JAZ?</el-menu-item>
        <el-menu-item index="2-3">Meet the Team</el-menu-item>
        <el-menu-item index="2-4">Working at JAZ</el-menu-item>
        <el-menu-item index="2-5">Our Community</el-menu-item>
        <el-menu-item index="2-6">Capabilities Statement</el-menu-item>
      </el-submenu>
      <el-menu-item index="3" disabled>Portfolio</el-menu-item>
      <el-menu-item index="4" disabled>Our Thinking</el-menu-item>
      <el-menu-item index="5" disabled>Resources</el-menu-item>
      <el-menu-item index="6" disabled>Contact</el-menu-item>
      <el-menu-item index="7" disabled
        ><i class="el-icon-s-shop"></i>
      </el-menu-item>
    </el-menu>
  </div>
</template>

<script>
export default {
  name: "Index",
};
</script>

<style scoped>
</style>
