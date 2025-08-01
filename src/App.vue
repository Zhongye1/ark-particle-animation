<script setup lang="ts">
import DynamicLogo from "./components/DynamicLogo.vue";
</script>

<template>
  <div class="app-container">
    <!-- 传入具体图片路径 -->
    <DynamicLogo logo-src="src\assets\logo_rhine.png" />
  </div>
</template>

<style scoped>
.app-container {
  width: 100vw;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #000000;
}
</style>
