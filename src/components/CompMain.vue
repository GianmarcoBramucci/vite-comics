<template>
    <div class="bg-black">
        <div class="container h-100 card3">
            <div v-for="comic in comics">
               <CompCard :img="comic.thumb" :tittle="comic.series"/>
            </div>
        </div>
    </div>
</template>

<script>
   import CompCard from './CompCard.vue';
   import { comics } from '../data/data.js';
    export default {
        name: 'CompMain',
        components:{
            CompCard
        },
        data(){
            return{
              comics
            }
        },
    }
</script>

<style lang="scss" scoped>
    .card3{
        height: 40%;
        display: flex;
        flex-wrap: wrap;
    }
    
</style>