<template>
    <h2>Get Input Field Value (11)</h2>
        <input type="text" placeholder="Enter email" v-model="email" />
        <br><br>
        <input type="password" placeholder="Enter password" v-model="password" />
        <br><br>
        <button v-on:click="getData()" type="button">Get Values</button>
        <br><br>    
    </template>
    
    <script>  
    export default {
        name: "GetInputFieldValue",    
        data() {
            return {
                email: null,
                password: null,
            }    
        },
    
        methods: {
            getData() {
                console.warn("Values:", this.email, this.password)
            }
        }//methods
    }
    </script>
    
    <style scoped>    
    h2 {
        color: rgb(0, 187, 255)
    }
    </style>
    