<template>
  <div>
    <p>数量{{msg}}</p>
    <br>
    <button v-on:click="addFn">+1</button>
    <button @click="subFn">-1</button>
    <button @click="DDD(5)">+5</button>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        msg: 1
      }
    },
    methods: {
      addFn() {
        this.msg++
      },
      subFn() {
        this.msg--
      },
      DDD(val) {
        this.msg += val
      }
    }
  }
</script>

<style scoped>

</style>