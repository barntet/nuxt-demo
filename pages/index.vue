<template>
  <div>
    <Header />
    <Content />
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import Header from "@/components/header.vue";
import contentA from "@/components/content.vue";

export default Vue.extend({
  components: {
    Header,
    contentA,
  },
  name: "IndexPage",
});
</script>
