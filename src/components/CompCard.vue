<template>
    <div>
        <img :src="img" alt="">
        <h5>{{tittle}}</h5>
    </div>
</template>

<script>
    export default {
        name: 'CompCard',
        props:[
            'img',
            'tittle'
        ]
    }
</script>

<style lang="scss" scoped>

</style>