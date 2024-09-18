<template>
    <h2>Dynamic Component (31)</h2>
    <button @click="tab='JavaComp'">Load Java</button>
    <br><br>
    <button @click="tab='NodeComp'">Load Node</button>
    <br><br>
    <button @click="tab='PhpComp'">Load Php</button>
    <component :is="tab" />
    <br><br>
</template>

<script>
    import JavaComp from './JavaComp.vue';
    import NodeComp from './NodeComp.vue';
    import PhpComp from './PhpComp.vue';

    export default{
        name: "DynamicComponent",

        components: {
            JavaComp, NodeComp, PhpComp
        },

        data()
        {
            return{
                tab:"JavaComp"
            }
        }
    }
</script>

<style scoped>    
    h2 {
        color: rgb(0, 187, 255)
    }
</style>
