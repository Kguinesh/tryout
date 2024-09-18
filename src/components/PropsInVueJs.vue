<template>
    <h2>Props in Vue Js (19)</h2>
    <StudentComponent :name="name" />
    <TeacherComponent name="John" />
    <br><br>
    
</template>

<script>
    import StudentComponent from './StudentComponent.vue';
    import TeacherComponent from './TeacherComponent.vue';
    
    export default {
        name: "PropsInVueJs",

        data() {
            return {
                name: "Bruce"
            }
        },
    
        components: {
            StudentComponent,
            TeacherComponent
        }

    }
</script>

<style scoped>
h2 {
    color: rgb(0, 187, 255)
}
</style>
    