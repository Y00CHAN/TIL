<script setup lang="ts">
import Counter from './components/Counter.vue';
import MessageDisplay from './components/MessageDisplay.vue';

const parantMessage = '나는 타입스크립트 공부중...'
</script>

<template>
  <h1>🎯 Vue + TS 기본 실습</h1>
  <MessageDisplay :message="parantMessage"/>
  <Counter />
</template>
