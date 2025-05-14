<template>
  <div :class="styles.message">
    <p>📩 메시지: {{ message }}</p>
  </div>
</template>

<script setup lang="ts">
import styles from '../styles/MessageDisplay.module.css'

defineProps<{
    message: string,
}>()
</script>

