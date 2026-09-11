<script setup>
import { ref } from 'vue'

const count = ref(0)
</script>

<template>
  <main class="wrap">
    <h1>🎉 Vue SPA 빌드 테스트</h1>
    <p>moveto.live의 "SPA 빌드" 탭을 테스트하기 위한 최소 Vue 3 + Vite 프로젝트입니다.</p>
    <button @click="count++">클릭 횟수: {{ count }}</button>
  </main>
</template>

<style scoped>
.wrap {
  max-width: 480px;
  margin: 4rem auto;
  padding: 2rem;
  font-family: system-ui, sans-serif;
  text-align: center;
}
button {
  margin-top: 1rem;
  padding: 0.6rem 1.2rem;
  font-size: 1rem;
  border-radius: 8px;
  border: 1px solid #ccc;
  cursor: pointer;
}
</style>
