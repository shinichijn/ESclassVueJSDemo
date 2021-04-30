<template>
  <div class="hello">
   <h1> {{test}} </h1>
  </div>
</template>

<script>

import Meal from './Meal.js';

const test = new Meal('We got a hambuger!!');

export default {
  name: "HelloWorld",
  data: () => ({
    test: test.eat()
  }),
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
