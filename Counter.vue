<template>
  <div>
   <p>I'm a Counter!</p>
   <br />
   <p>Current count is {{ count }} </p>
   <button v-on:click = "count += 1">Increase</button>
   <button v-on:click = "count -= 1">Decrease</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      count: 0
    };
  }
};
</script>

<style>
</style>

