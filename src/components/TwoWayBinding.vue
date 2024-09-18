<template>
    <h2>Two way binding (10)</h2>
        <input type="text" v-model="count">
        <h3>{{count}}</h3>
        <br><br>
    
    </template>
    
    <script>
    
    export default {
        name: "TwoWayBinding",
    
        data() {
            return {
                count: 0
            }
        },
    }
    </script>
    
    <style scoped>
    h2 {
        color: rgb(0, 187, 255)
    }
    </style>
    