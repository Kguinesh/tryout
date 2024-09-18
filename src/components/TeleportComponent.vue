<template>
    <h2>Teleport Component (32)</h2>
    <teleport to="#footer">
        <FooterComp />
    </teleport>
</template>

<script>
    import FooterComp from './FooterComp.vue';
    export default {
        name: "TeleportComponent",

        components: {
            FooterComp
        }
    }
</script>

    
<style scoped>
    h2 {
        color: rgb(0, 187, 255)
    };

</style>
