<template>
    <h2>Non Props Data (26)</h2>
    <User2Comp data="some data" id="user-cmp" />
    <br><br>
    
</template>
    
<script>
    import User2Comp from './User2Comp.vue';

    export default {
        name: "NonPropsData",

        components: {
            User2Comp
        }
    
    }
</script>
    
<style scoped>    
    h2 {
        color: rgb(0, 187, 255)
    }
</style>
    