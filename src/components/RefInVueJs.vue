<template>
    <h2>Ref in Vue Js (21)</h2>
    <input type="text" ref="input">
    <button v-on:click="getData">Click Me</button>
    <br><br><br>
</template>

<script>
export default {
    name: "RefInVueJs",

    methods: {
        getData(){
            this.$refs.input.focus(); 
            //$refs.input.focus() 
               //is used to directly access an input element (or other DOM element) 
               //via its ref and programmatically set the focus on it.
            let val=this.$refs.input.value;
            //$refs.input.value 
              //used to directly access the value property of an input element (or 
              //other form element) via its ref, allowing you to get or set the 
              //current value of the input field.       
            console.warn(val)
            this.$refs.input.style.color="red";
            //$refs.input.style.color 
              //is used to access or modify the inline CSS color property of an 
              //input element (or any DOM element) via its ref, allowing you to 
              //get or set the text color of the element.

        }
        
    }
}
</script>

    
<style scoped>
    h2 {
        color: rgb(0, 187, 255)
    }
</style>
