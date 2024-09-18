<template>
    <h2>Send Data Child to Parent in Vue Js (20)</h2>
    <h2>{{childUser}}</h2>
    <User1Comp :getUser="getUsername" />
    <br><br><br>
</template>

<script>
    import User1Comp from './User1Comp.vue';

    export default {
        name: "SendDataChildParent",

        data() {
            return {
                childUser: ""
            }
        },

        components: {
            User1Comp
        },

        methods: {
            getUsername(name) {
                this.childUser = name
            }

        }
    }
</script>

<style scoped>
h2 {
    color: rgb(0, 187, 255)
}
</style>
