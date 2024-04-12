<template>
        <CompIconStash/>
        <CompLinck/>
        <CompSocial/>
</template>

<script>
    import CompIconStash from "./CompIconStash.vue";
    import CompLinck from "./CompLinck.vue";
    import CompSocial from "./CompSocial.vue";
    export default {
        name: 'CompFooter',
        components:{
            CompIconStash,
            CompLinck,
            CompSocial
        }
    }
</script>

<style lang="scss" scoped>

</style>