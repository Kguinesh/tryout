<template>
    <h2>Interpolation And Data (7)</h2>
    <h3>Email: {{email}}</h3>
    <h3>Mobile: {{mobile}}</h3>
    <h3>Name: {{getName("Peter")}}</h3>
    <br><br>
</template>

<script>
    export default {
        name: "InterpolationAndData",

        data(){
            return{
                email:"Peter@test.com",
                mobile:8888,

                getName: function(a)
                {
                    return a;
                }
            }
        }

    }
</script>

<style scoped>
    h2 {
        color: rgb(0, 187, 255)
    }
</style>
