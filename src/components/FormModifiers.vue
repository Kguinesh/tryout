<template>
    <h2>Form Modifiers (25)</h2>
    <input type="number" v-model.number="data" />
    <h3>Data is:{{typeof(data)}}</h3>
    <br><br>
</template>

<script>
    export default{
        name:"FormModifiers",

        data(){
            return{
                data: ""
            }
        }
    }
</script>

<style scoped>

h2{
    color: rgb(0, 187, 255)
}
</style>