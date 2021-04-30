<template>
  <div class="flex flex-row justify-around">
    <a href="https://github.com/Albin-Sander" class="">
      <picture>
        <source
          srcset="../assets/github-light.png"
          media="(prefers-color-scheme: dark)"
        />
        <img
          src="../assets/github.png"
          alt="moving car"
          class="md:h-12 md:w-12 h-8 w-8 animate-fade-in-down dark:text-white"
        />
      </picture>
    </a>
    <a href="mailto:albinsander17@gmail.com" class="animate-fade-in-down">
      <MailIcon class="md:h-12 md:w-12 h-8 w-8 dark:text-white" />
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
