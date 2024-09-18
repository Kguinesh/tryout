<template>
    <h2>Methods (8)</h2>
    <h3>Email: {{email}}</h3>
    <h3>Name: {{getName("Peter")}}</h3>
    <h3>All Data: {{getData()}}</h3>
    <br><br>
</template>
<script>
    export default {
        name: "MethodsComp",

        data(){
            return{
                email:"john@test.com",
            }
        },

        methods: {
            getName(name) {
                return name;
            },

            getData(){
                return {
                    name: 'John',
                    email: this.email
                }
            }
        }
    }
</script>
<style scoped>
    h2 {
        color: rgb(0, 187, 255)
    }
</style>