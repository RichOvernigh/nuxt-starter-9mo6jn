<template>
  <div class="title">Page2</div>
  <NuxtLink class="btn m-3 text-sm" to="/"> Back </NuxtLink>
  <NuxtLink class="btn m-3 text-sm" to="/page3">To Page3 </NuxtLink>
  <NuxtLink class="btn m-3 text-sm" to="/page3">To Page3 </NuxtLink>
  <NuxtLink class="btn m-3 text-sm" to="/page3">To Page3 </NuxtLink>
</template>
<script>
export default {
  layout: 'custom',
};
</script>
<style>
.title {
  font-size: 30px;
  font-weight: bold;
  color: red;
}
</style>
