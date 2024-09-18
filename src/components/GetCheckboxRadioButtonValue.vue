<template>
    <h2>Get Checkbox & Radio Button Value (12)</h2>
    
    <h3>Technology</h3>
    <label for="java">Java</label>
    <input type="checkbox" value="java" v-model="technology" id="java">
    <br><br>
    <label for="php">PHP</label>
    <input type="checkbox" value="php" v-model="technology" id="php">
    <br><br>
    <label for="node">Node</label>
    <input type="checkbox" value="node" v-model="technology" id="node">
    <br><br>

    <h3>Who I am</h3>
    <label for="student">Student</label>
    <input type="radio" value="student" v-model="who" name="who" id="student">
    <br><br>
    <label for="developer">Developer</label>
    <input type="radio" value="developer" v-model="who" name="who" id="developer">

    <h4>Selected Technology: {{technology}}</h4>
    <h4>I am a: {{who}}</h4>
    <br><br>
    
</template>
    
<script>
    export default {
        name: "GetCheckboxRadioButtonValue",
    
        data() {
            return {
                technology: [],
                who:null,
            }
    
        },
    }
    </script>
    
    <style scoped>
    h2 {
        color: rgb(0, 187, 255)
    }
    </style>
    