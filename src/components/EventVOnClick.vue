<template>
    <h2>Event V On Click (9)</h2>
    <h3 v-on:mousemove="getConsole()">Event</h3>
    <button v-on:click="getData()">Click Me</button><br><br>
    <button v-on:dblclick="getData()">Double Click Me</button> 
    <h3>{{count}}</h3>
    <br><br>
</template>

<script>
    export default{
        name:'EventVOnClick',

        data(){
            return{
                count:0
            }
        },

        methods:{
            getData()
            {
                this.count= this.count+1;
            },

            getConsole(){
                console.warn("Function Called")
            }
        }
    }
</script>

<style scoped>
    h2 {
        color: rgb(0, 187, 255)
    }
</style>
