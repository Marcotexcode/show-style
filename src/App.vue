<template>
 
  <div id="app">

    <Header/>

    <Show/>


  
  </div>

</template>



<script>

  import Header from '@/components/Header.vue'
  import Show from '@/components/Show.vue'



  export default {
    name: 'App',
    components: {

      Header,
      Show

    }
  }

</script>

<style lang="scss">

    @import '@/style/general';
    @import '@/style/commons';

</style>
