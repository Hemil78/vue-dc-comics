<template>

  <div id="app" >

    <header>

      <section class="container">
        <Header/>
      </section>
      
    </header>

    <main>

      <section class="content">
        <div class="container">
          <Components/>
        </div>
      </section>

      <section class="digital">
        <div class="container">
          <Digital/>
        </div>
      </section>
      
    </main>
    
    <footer>

      <section class="footer-up">
        <div class="container">
          <FooterUp/>
        </div>
      </section>

      <section class="footer-down">
        <div class="container">
          <FooterDown/>
        </div>
      </section>
      
      
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

@import "./assets/style/common";



</style>
