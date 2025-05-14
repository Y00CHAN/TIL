<!-- Counter.vue -->
<template>
  <div :class="styles.message">
    <h2>🧮 카운터</h2>
    <p>현재 숫자: {{ count }}</p>
    <button @click="increase">+1</button>
    <button @click="decrease">-1</button>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue';
import styles from '../styles/MessageDisplay.module.css'

const count = ref<number>(0)

const increase = () => {
  count.value+=10
}

const decrease = () => {
  count.value--
}

</script>

<style scoped>

</style>
