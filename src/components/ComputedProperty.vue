<template>
    <h2>Computed Property (27)</h2>
    <h3>{{getResultMethod()}}</h3>
    <h3>{{getResult}}</h3>
    <br><br>
</template>
    
<script>
    
    export default {
        name: "ComputedProperty",

        data(){
            return{
                dollars:100,
                rupeeVal:70,
                discount:10,
            }          
        },

        methods:{
            getResultMethod(){
                return (this.dollars*this.rupeeVal)-this.discount;
            }
        },
        
        computed: {
            getResult(){
                return (this.dollars*this.rupeeVal)-this.discount;
            }
        }
    
    }
</script>
    
<style scoped>    
    h2 {
        color: rgb(0, 187, 255)
    }
</style>
    