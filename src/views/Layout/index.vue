<template>
  <Header />
  <div class="con">
    <Main />
  </div>
</template>

<script setup>
import Header from './Header/index.vue'
import Main from './Main/index.vue'
</script>

<style lang="scss" scoped>
.con {
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
