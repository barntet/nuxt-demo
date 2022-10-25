<template>
  <div class="content">
    <Left />
    <Center />
    <Right />
  </div>
</template>

<script setup>
import Left from "./left.vue";
import Center from "./center.vue";
import Right from "./right.vue";
</script>

<style scoped>
.content {
  display: flex;
  justify-content: space-between;
}

.left {
  width: 300px;
  height: 100%;
}

.center {
  flex: 1;
}

.right {
  width: 200px;
  height: 100%;
}
</style>
