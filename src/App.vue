<script setup>
import { ref, reactive} from "vue";
const jokes= reactive({
  value : "Chuck Norris can prepare a Vegan dish out of pork, beef, chicken, eggs, milk, and butter."
});



</script>

<template>
  <section class="flex-col  justify-content-center align-items-center ">
    <p class="font-bold">{{ jokes.value }}</p>
    <button @click=" getJokes()" class="bg-green-600 p-3 text-white mt-3 " >Get a new Joke</button>
  </section>
</template>

<style scoped>

</style>
