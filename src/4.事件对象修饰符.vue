<template>
  <div @click="father">
    <a href="http:www.baidu.com" @click.prevent.stop="son">去百度</a> 
    <p @click.once="one">333</p>
  </div>
</template>

<script>
  export default {
    data() {
      return {

      }
    },
    methods: {
      father() {
        console.log(222);
      },
      son() {
        console.log(111);
      },
      one() {
        console.log(333);
      }
    }
  }
</script>

<style scoped>

</style>