<template>
  <div class="p-6 max-w-sm mx-auto bg-white rounded-xl shadow-md flex items-center space-x-4">
    <div class="flex-shrink-0">
      <img class="h-12 w-12" src="../assets/logo.png" alt="ChitChat Logo">
    </div>
    <div>
      <div class="text-xl font-medium text-black">ChitChat</div>
      <p class="text-gray-500">{{text}}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "InputField",
  props: {
    text: String,
  },
};

</script>

<style scoped>

</style>
