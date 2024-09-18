<template>
    <h3>Student Data</h3>
    <h4>Student Name is: {{name}}</h4> 
</template>
<script>
    
    export default{
        name: 'StudentComponent',

        props: {
            name:String
        }

    }
</script>

<style scoped>
    h3 {
    color: rgb(0, 21, 255)
    }
</style>