<template>
<div class="user">
    <h3>{{data.name}}</h3>
    <h3>{{data.email}}</h3>
    <button v-on:click="getData(data.name)">Alert Name</button>
</div>
</template>

<script>
 export default {
     name: 'UserComponent',

     props: {
        data:Object,
        getData:Function
     }
 }
</script>

<style>
.user{
    background-color: skyblue;
    padding: 10px;
    border-bottom: 1px solid;
    margin-bottom: 20px;
    list-style-position: inside;
}
</style>