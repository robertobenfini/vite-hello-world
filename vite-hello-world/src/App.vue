<script>
 import AppTitle from './components/AppTitle.vue';
 import AppHero from './components/AppHero.vue';

 export default {
     components:{
       AppTitle,
       AppHero
   }
 }
</script>

<template>
  
  <body>
    <div>
      <AppTitle />
    </div>

    <div>
      <AppHero />
    </div>
  </body>

</template>

<style scoped>
  
</style>