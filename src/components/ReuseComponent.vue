<template>
    <h2>Reuse Component (16)</h2>
    <ul>
        <li v-for="item in users" :key="item.name">
            <UserComponent :data=item :getData="getData" />
    
        </li>
    </ul>
    <br><br>
    </template>
    
    <script>
    import UserComponent from './UserComponent.vue';
    
        export default {
            name: "ReuseComponent",
    
            components: {
                UserComponent
            },

            methods: {
                getData(name)
                {
                    alert(name)
                }

            },
    
            data() {
                return {
                    users: [{
                            name: 'Maria',
                            email: 'maria@test.com'
                        },
                        {
                            name: 'Bruce',
                            email: 'bruce@test.com'
                        },
                        {
                            name: 'Sam',
                            email: 'sam@test.com'
                        },
                        {
                            name: 'Catia',
                            email: 'catia@test.com'
                        }
                    ]
    
                }
            }
            
        }
    </script>
    
    <style scoped>    
    h2 {
        color: rgb(0, 187, 255)
    }
    </style>
    