<template>
    <h2>CSS Binding (18)</h2>
    <h3 :class="applyStyle">Green</h3>
    <br>
    <button v-on:click="colorfull=!colorfull">Apply Style</button>
    <br><br><br>
</template>
    
<script>
    export default {
        name: "CSSBinding",
        data()
        {
            return {
                colorfull:true
            }
        },

        computed:{
            applyStyle(){
                return{
                    green: this.colorfull,
                    err:true,
                    other:true

                }
            }

        }

    }
</script>
    
<style scoped>
    h2 {
        color: rgb(0, 187, 255)
    }

    .green{
        margin: auto;
        background-color: green;
        width:200px;
        padding: 15px;
    }

    .err{
        color: deeppink;
    
    }

    .other{
        font-size: 20px;
    }
</style>
    