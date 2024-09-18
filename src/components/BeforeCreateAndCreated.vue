<template>
    <h2>Life Cycle Method (33)</h2>
    <h3>beforeCreate and created (34)</h3>
</template>

<script>
    export default {
        name: 'BeforeCreateAndCreated',

        data() {
            console.warn("created");
        },

        beforeCreate(){
            alert("Before Created");
        },

        created(){
            alert("Created");
        }
    }
</script>
<style scoped>
    h2 {
        color: rgb(0, 187, 255)
    };

</style>