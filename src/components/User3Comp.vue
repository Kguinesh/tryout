<template>
    <h4 ref="user">User Component</h4>
</template>

<script>

    export default {
        name: "User3Comp",
        
        beforeUnmount(){
            console.log("Before Unmount", this.$refs["user"]);
        },

        unmounted(){
            console.log("Unounted", this.$refs["user"]);
        }

    }
</script>

<style scoped>
    h2 {
        color: rgb(0, 187, 255)
    }
</style>
    