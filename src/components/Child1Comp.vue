<template>
    <h3>{{data}}</h3>
        <header>
            <slot name="header"></slot>
        </header>
        <br>
    <div class="cart">    
        <content>
            <slot name="main"></slot>
        </content>
        <content>
            <slot name="content"></slot>
        </content>
        <footer>
            <slot name="footer"><button>Buy</button></slot>
        </footer>
    </div>    
</template>
    
<script>   
    export default {
        name: "Child1Comp",

    }
</script>

<style>
    .cart{
        border: 1px solid;
        width: 170px;
        text-align: center;
        padding: 20px;
        margin: auto;
    }
</style>
    
    