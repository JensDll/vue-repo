<template>
  <h1>Title</h1>
  <WithDot />
  <WithoutDot />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import WithDot from "./.foo/Test.vue";
import WithoutDot from "./foo/Test.vue";

export default defineComponent({
  components: {
    WithDot,
    WithoutDot,
  },
});
</script>

<style></style>
