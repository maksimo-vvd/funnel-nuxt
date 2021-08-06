<template>
  <nav class="bg-gray-700 text-center p-5 text-white">
    <NuxtLink class="mx-4" to="/">Home</NuxtLink>
    <NuxtLink class="mx-4" to="/fun">Fun</NuxtLink>
    <NuxtLink class="mx-4" to="/more-fun">More Fun</NuxtLink>
<!--    <NuxtLink class="mx-4" to="/step1">Step 1</NuxtLink>-->
<!--    <NuxtLink class="mx-4" to="/step2">Step 2</NuxtLink>-->
<!--    <NuxtLink class="mx-4" to="/step3">Step 3</NuxtLink>-->
    <NuxtLink class="mx-4" to="/results">Results</NuxtLink>
    <NuxtLink class="mx-4" to="/posts">Posts</NuxtLink>
    <NuxtLink class="mx-4" to="/">Left</NuxtLink>
    <NuxtLink class="mx-4" to="/">Right</NuxtLink>
  </nav>
</template>

<script>
export default {
  name: "Nav.vue"
}
</script>

<style scoped>

</style>
