<template>
    <div>
        <input type="text" name="" id="" :value="val" @input="fn">
    </div>
</template>

<script>
    export default {
        data() {
            return {
                val: ''
            }
        },
        methods: {
            fn(e) {
                this.val = e.target.value
            }
        }
    }
</script>

<style scoped>

</style>