<template>
 
  <div id="app">

    <Header/>

    <Show/>
    
    <BannerMap/>

    <ContactForm/>
    
    <Footer/>
  
  </div>

</template>



<script>

  import Header from '@/components/Header.vue'
  import Show from '@/components/Show.vue'
  import BannerMap from '@/components/BannerMap.vue'
  import ContactForm from '@/components/ContactForm.vue'
  import Footer from '@/components/Footer.vue'



  export default {
    name: 'App',
    components: {

      Header,
      Show,
      BannerMap,
      ContactForm,
      Footer
    }
  }

</script>

<style lang="scss">

    @import '@/style/general';
    @import '@/style/commons';

</style>
