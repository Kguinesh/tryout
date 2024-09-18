<template>
    <h3>User Component</h3>
    <button v-on:click="getUser(username)">Send User Name</button>
</template>

    
<script>
    export default {
        name: 'User1Comp',

        data() {
            return {
                username: "Peter"
            }
        },

        props: {
            getUser: Function

        }
    }
</script>

    
<style>
h3 {
    color: rgb(0, 21, 255)
}
</style>
