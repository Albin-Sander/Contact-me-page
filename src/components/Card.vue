<template>
  <div
    class="border-solid border-2 border-black dark:border-purple-400 w-100 h-96 bg-white flex flex-col justify-center rounded-lg dark:bg-gray-700 dark:text-white"
  >
    <h1
      class="flex justify-center mb-4 mt-4 md:text-4xl animate-fade-in-down font-bold dark:text-white underline"
    >
      Tech Stack
    </h1>
    <div class="flex flex-row justify-around">
      <a href="https://developer.mozilla.org/en-US/docs/Web/HTML">
        <img
          src="../assets/svg/html.svg"
          alt="HTML"
          class="md:h-12 md:w-12 h-8 w-8 animate-fade-in-down dark:text-white"
        />
      </a>

      <a href="https://developer.mozilla.org/en-US/docs/Web/CSS">
        <img
          src="../assets/svg/css.svg"
          alt="CSS"
          class="md:h-12 md:w-12 h-8 w-8 animate-fade-in-down dark:text-white"
        />
      </a>
      <a href="https://www.javascript.com/">
        <img
          src="../assets/svg/javascript.svg"
          alt="Javascript"
          class="md:h-12 md:w-12 h-8 w-8 animate-fade-in-down dark:text-white"
        />
      </a>
    </div>

    <div class="flex flex-row justify-around mt-10">
      <a href="https://www.typescriptlang.org/">
        <img
          src="../assets/svg/typescript.svg"
          alt="Typescript"
          class="md:h-12 md:w-12 h-8 w-8 animate-fade-in-down dark:text-white"
        />
      </a>
      <a href="https://reactjs.org/">
        <img
          src="../assets/svg/react.svg"
          alt="React"
          class="md:h-12 md:w-12 h-8 w-8 animate-fade-in-down dark:text-white"
        />
      </a>
      <a href="https://vuejs.org/">
        <img
          src="../assets/svg/vue.svg"
          alt="Vue"
          class="md:h-12 md:w-12 h-8 w-8 animate-fade-in-down dark:text-white"
        />
      </a>
    </div>

  <div class="flex flex-row justify-around mt-10">
  <a href="https://www.swift.org/">
  <img
  src="../assets/svg/swift.svg"
  alt="Swift"
  class="md:h-12 md:w-12 h-8 w-8 animate-fade-in-down dark:text-white mt-6 mr-4"
  />
  </a>
  <a href="https://developer.apple.com/xcode/swiftui/">
  <img
  src="../assets/svg/swiftui.svg"
  alt="SwiftUI"
  class="md:h-16 md:w-24 h-13 w-12 animate-fade-in-down dark:text-white ml-4 mt-4"
  />
  </a>
  </div>




    </div>

</template>

<script>
export default {
  name: "CardInfo",
};
</script>
