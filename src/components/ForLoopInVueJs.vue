<template>
    <h2>For Loop in Vue js (14)</h2>
    <div class="container">
        <ul>
            <li v-for="item in technology" :key="item">
                {{item}}
            </li>
        </ul>
        
    
        <ul>
            <li v-for="item in user" :key="item">
                Name is {{item.name}} and Email is {{item.email}}
            </li>
        </ul>
    </div>    
    <br><br>    
</template>
    
<script>
    export default {
        name: "ForLoopInVueJs",
        
        data() {
            return {
                user:[
                    {
                        name: "Maria",
                        email: 'maria@test.com'
                    },
                    {
                        name: "Sam",
                        email: 'sam@test.com'
                    },
                ],    

                technology:['java','php','node', 'html'],
            }
    
        },
    }
</script>
    
<style scoped>
    h2 {
        color: rgb(0, 187, 255)
    }

    .container {
        text-align: center;
        list-style-position: inside;
    }    
</style>
    
