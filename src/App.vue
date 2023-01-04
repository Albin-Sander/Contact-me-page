<template>
  <div class="h-screen flex items-center justify-center dark:bg-gray-800">
    <div class="flex-col">
      <Name />
      <Github />
    </div>
  </div>
</template>

<script>
import Name from "./components/Name";
import Github from "./components/Github";

export default {
  name: "App",
  components: {
    Name,
    Github,
  },
  created() {
    document.title = "Albin Sander";
  },
};
</script>

<style></style>
