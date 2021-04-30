<template>
  <div class="flex flex-row justify-around">
    <a href="https://github.com/Albin-Sander">
      <img
        src="../assets/github-light.png"
        class="md:h-12 md:w-12 h-8 w-8 animate-fade-in-down hover:animate-bounce"
      />
    </a>
    <a href="mailto:albinsander17@gmail.com" class="animate-fade-in-down">
      <MailIcon class="md:h-12 md:w-12 h-8 w-8 text-white" />
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
