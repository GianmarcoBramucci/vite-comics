<template>
  <CompHeader/>
  <CompMain/>
  <CompFooter/>
</template>

<script>
   import CompHeader from './components/CompHeader.vue';
   import CompMain from './components/CompMain.vue';
   import CompFooter from './components/CompFooter.vue';
  export default {
    name:'App',
    components:{
      CompHeader,
      CompMain,
      CompFooter
    }
  }
</script>

<style lang="scss" scoped>

</style>


