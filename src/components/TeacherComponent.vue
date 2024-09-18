<template>
    <h3>Teacher Data</h3>
    <h4>Teacher Name is: {{name}}</h4>
</template>
<script>
    
    export default{
        name: 'TeacherComponent',

        props: {
            name: String
        }
    }
</script>

<style scoped>
    h3 {
        color: rgb(0, 21, 255)
    }
</style>