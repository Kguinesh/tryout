<template>
    <h2>Slots in Vue.js (30)</h2>
    <Child1Comp>
        <template v-slot:header>
            <h3>Code Step by Step</h3>
            <a href="#">Code Step by Step</a><br>
            <img src="./image.png" />
            <br>
        </template>
        <template v-slot:main>
            <h3>Peter</h3>
        </template>
        <template v-slot:content>
            <p>A Vue js product</p>
        </template>

        <template v-slot:footer>
        </template>
    </Child1Comp>
    <br><br>
</template>

<script>
    import Child1Comp from './Child1Comp.vue';
    export default {
        name: "SlotsInVueJs",

        components: {
            Child1Comp
        }

    };
</script>

<style scoped>
    h2 {
        color: rgb(0, 187, 255)
    }
</style>
