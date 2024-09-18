<template>
<h3>{{name}}</h3>
<h3>{{user.name}}</h3>
<button v-on:click="getData()">Called Function</button>
</template>

<script>
export default {
    name: 'ChildComponent',
    props: {
        name: String,
        user: Object,
        getData: Function
    }

}
</script>
