<template>
  <div class="flex flex-row justify-around">
    <a href="https://github.com/Albin-Sander">
      <img
        src="../assets/github-light.png"
        class="h-12 w-12 animate-fade-in-down hover:animate-bounce"
      />
    </a>
    <a href="mailto:albinsander17@gmail.com" class="animate-fade-in-down">
      <MailIcon class="h-12 w-12 text-white" />
    </a>
  </div>
</template>

<script>
import { MailIcon } from "@heroicons/vue/outline";
export default {
  name: "Github",
  components: {
    MailIcon,
  },
};
</script>

<style></style>
