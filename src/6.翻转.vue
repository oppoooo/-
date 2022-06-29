<template>
  <div>
    <h1>{{msg}}</h1>
    <button @click="btn">翻转</button>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        msg: 'hello, vue'
      }
    },
    methods: {
      btn() {
        this.msg = this.msg.split('').reverse().join('')
      }
    }
  }
</script>

<style scoped>

</style>