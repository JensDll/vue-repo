<template>
  <h1>Title</h1>
  <WithDot />
  <WithoutDot />
</template>

<script lang="ts">
import { defineComponent, ref } from "vue";
import WithDot from "./.foo/Test.vue";
import WithoutDot from "./foo/Test.vue";

let x: string;
x = 10;

export default defineComponent({
  components: {
    WithDot,
    WithoutDot,
  },
});
</script>

<style></style>
