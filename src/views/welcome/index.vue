<script setup lang="tsx">
import { ref } from "vue";

defineOptions({
  name: "Welcome",
  render() {
    const count = ref(0);
    setTimeout(() => {
      count.value++;
    }, 1000);
    return <h1>you{count}</h1>;
  }
});
</script>

<template>
  <div>nihao</div>
</template>
