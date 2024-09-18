<template>
    <h2>If Else Condition (13)</h2>
    <h3 v-if="show">If Condition</h3>
    <h3 v-else>Else Condition</h3>
    <button v-on:click="show=!show">Toogle</button>
    <br><br><br>
</template>

<script>
export default {
    name: "IfElseCondition",

    data() {
        return {
            show: true
        }
    }
}
</script>

    
<style scoped>
    h2 {
        color: rgb(0, 187, 255)
    }
</style>
