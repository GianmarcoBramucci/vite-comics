<template>
    <div class="container">
        <div class="d-flex justify-content-between align-items-center">
            <div>
                <img :src="logoSrc" alt="">
            </div>
            <div>
                <CompNav/>
            </div>
        </div>

    </div>
</template>

<script>
    import CompNav from "./CompNav.vue";
    export default {
        name: 'CompHeader',
        components:{
            CompNav
        },
        data(){
            return{
                logoSrc: '/img/dc-logo.png'
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>