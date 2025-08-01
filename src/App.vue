<script setup lang="ts">
import DynamicLogo from "./components/DynamicLogo.vue";
</script>

<template>
  <div class="app-container">
    <!-- 传入具体图片路径 -->
    <DynamicLogo logo-src="https://pica.zhimg.com/v2-164f0c352e3898a34f68dac4c11c9304_1440w.jpg" />
  </div>
</template>

<style scoped>
.app-container {
  width: 100vw;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #b3b3b3;
}
</style>
