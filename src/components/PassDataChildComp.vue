<template>
    <h2>Pass Data to child Component (15)</h2>
    <ChildComponent name="Khush" :user="user" :getData="getData" />
    <br><br><br>
</template>

<script>
import ChildComponent from './ChildComponent.vue';

export default {
    name: "PassDataChildComp",

    components: {
        ChildComponent,
    },

    data() {
        return {
            user: {
                name: 'Peter',
                email: 'peter@test.com'
            }
        }

    },

    methods: {
        getData() {
            console.warn("Parent function called")
            alert("Hello")
        }

    }
}
</script>

<style scoped>
    h2 {
        color: rgb(0, 187, 255)
    }
</style>
