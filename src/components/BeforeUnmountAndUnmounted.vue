<template>
    <h3>beforeUnmount and unmounted (37)</h3>
    <User3Comp v-if="show"/>
    <button v-on:click="show=!show">Toogle</button>  
    <br><br><br>
</template>

<script>
import User3Comp from './User3Comp.vue';

    export default {
        name: 'BeforeUnmountAndUnmounted',

        data() {
            return{
                show:true
            }
        },

        components: {
            User3Comp
        }
    }
</script>

<style scoped>
    h2 {
        color: rgb(0, 187, 255)
    };

</style>