<template>
  <div>
    <div class="title">Page1</div>
    <div class="test">eeee.</div>
    <div>{{ test }}</div>
    <input type="text" v-model="test" />
    <NuxtLink to="/page2">To page 2</NuxtLink>
  </div>
</template>

<script setup>
import { ref, watch } from 'vue';
const test = ref(1);
watch(test, (val) => {
  console.log(val, '===val');
});
</script>

<style>
* {
  margin: 0;
  padding: 0;
}
.test {
  width: 300px;
  height: 300px;
  background: red;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
