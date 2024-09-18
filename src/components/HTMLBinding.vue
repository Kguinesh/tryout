<template>
    <h2>HTML Binding (17)</h2>
    <h3>{{text}}</h3>
    <div v-html="tag"></div>
    <div v-html="tag2"></div>
    <br><br>

    </template>
    
    <script>
    
        export default {
            name: "HTMLBinding",
    
            data(){
                return {
                    text:"Khush",
                    tag:"<h3>Khushali</h3>",
                    tag2:"<h3>khushali@test.com</h3>"
                }
    
            }
    
        }
    </script>
    
    <style scoped>
    h2 {
        color: rgb(0, 187, 255)
    }
    </style>
    