<template>

  <div id="app" >

    <header>

      <section class="container">
        <Header/>
      </section>
      
    </header>

    <main>

      <section class="jumbo">
        <div class="container">
          <Jumbotron/>
        </div>
      </section>

      <section class="content">
        <div class="container reset-padding">
          <LibraryHero/>
        </div>
      </section>

      <section class="digital">
        <div class="container">
          <Digital/>
        </div>
      </section>
      
    </main>
    
    <footer>

      <section class="footer-up footerUp-bg">
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
  import Jumbotron from '@/components/Jumbotron.vue';
  import LibraryHero from '@/components/LibraryHero.vue';
  import Digital from '@/components/Digital.vue';
  import FooterUp from '@/components/FooterUp.vue';
  import FooterDown from '@/components/FooterDown.vue';

export default {
  name: 'App',
  components: {
    Header,
    Jumbotron,
    LibraryHero,
    Digital,
    FooterUp,
    FooterDown
  }
}

</script>

<style lang="scss">

@import "./assets/style/common";



</style>
