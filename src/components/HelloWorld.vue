<template>
  <div class="hello">
    <input
      class="bg-white focus:outline-none focus:shadow-outline border border-gray-300 rounded-lg py-2 px-4 block w-full appearance-none leading-normal"
      type="email"
      placeholder="jane@example.com"
    />
    <p class="text-large text-red-500 hover:text-blue-500">Blue Text</p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
};
</script>
<style scoped></style>
