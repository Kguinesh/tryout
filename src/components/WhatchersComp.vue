<template>
    <h2>Whatchers Comp (28)</h2>
    <h3>{{count}}</h3>
    <button v-on:click="count=count+1">+</button>
    <button v-on:click="count=count-1">-</button>
    <br><br>
</template>
    
<script>
    
    export default {
        name: "WhatchersComp",

        data() {
            return {
                count:0
            }
        },

        watch: {
            count(val,prev)
            {
                if(val>5 && val>prev)
                {
                    this.count=0
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
    