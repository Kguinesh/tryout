<template>
    <h3>beforeUpdate and updated (36)</h3>
    <h4 ref="count">{{counter}}</h4>
    <button v-on:click="counter=counter+1">Update Count</button>
</template>

<script>
    export default {
        name: 'BeforeUpdateAndUpdated',

        data() {
            return{
                counter:0
            }
        },

        beforeUpdate(){
            console.warn("Before Update", this.$refs["count"].textContent);
        },

        updated(){
            console.warn("Updated",this.$refs["count"].textContent);
        }
    }
</script>

<style scoped>
    h2 {
        color: rgb(0, 187, 255)
    };

</style>