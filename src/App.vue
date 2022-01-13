<template>
  <div class="h-screen flex items-center justify-center dark:bg-gray-800">
    <div class="flex-col">
      <Name />
      <Github />
      <Card class="mt-20" />
    </div>
  </div>
</template>

<script>
import Card from "./components/Card.vue";
import Name from "./components/Name";
import Github from "./components/Github";

export default {
  name: "App",
  components: {
    Name,
    Github,
    Card,
  },
  created() {
    document.title = "Albin Sander";
  },
};
</script>

<style></style>
