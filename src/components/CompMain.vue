<template>
    <div class="bg-black">
        <div class="container">
            <div>
                {{ card }}
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'CompMain',
        data(){
            return{
                card: 'qui andranno card'
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>