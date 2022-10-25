<template>
  <div>
    <div>{{ props.value.title }}</div>
    <Tree v-if="value.children && props.value.children.length" />
  </div>
</template>

<script setup>
const props = defineProps(["value"]);
</script>

<style lang="scss" scoped></style>
