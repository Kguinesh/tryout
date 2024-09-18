<template>
    <h3>beforeMount and mounted (35)</h3>
</template>

<script>
    export default {
        name: 'BeforeMountAndMounted',

        beforeMount(){
            console.warn("Before Mount", this.$el);
        },

        mounted(){
            console.warn("Mounted",this.$el);
        }
    }
</script>
<style scoped>
    h2 {
        color: rgb(0, 187, 255)
    };

</style>