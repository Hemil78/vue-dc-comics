<template>

  <div id="app">

    <Header/>

    <main>
      <Components/>
      <Digital/>
    </main>
    
    <footer>
      <FooterUp/>
      <FooterDown/>
    </footer>
    
  </div>

</template>

<script>
  
  import Header from '@/components/Header.vue';
  import Components from '@/components/Components.vue';
  import Digital from '@/components/Digital.vue';
  import FooterUp from '@/components/FooterUp.vue';
  import FooterDown from '@/components/FooterDown.vue';

export default {
  name: 'App',
  components: {
    Header,
    Components,
    Digital,
    FooterUp,
    FooterDown
  }
}

</script>

<style lang="scss">
#app {
  
}
</style>
