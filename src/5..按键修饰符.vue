<template>
  <div>
    <input type="text" @keydown.enter="one">
    <br>
    <input type="text" @keyup.esc="two">
  </div>
</template>

<script>
  export default {
    methods: {
      one() {
        alert('enter')
      },
      two() {
        alert('esc')
      }
    }
  }
</script>

<style scoped>

</style>