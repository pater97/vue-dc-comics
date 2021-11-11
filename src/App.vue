<template>
  <div id="app">
    <!-- header -->
    <header id="site_header">
      <siteHeader/>
    </header>
    <!-- main -->
    <main id="main_site">
      <siteMain/>
    </main>
    <!-- footer -->
    <footer id="site_footer">
      <siteFooter/>
    </footer>
  </div>
</template>

<script>
// imporazione
import siteHeader from './components/siteHeader.vue'
import siteMain from './components/siteMain.vue'
import siteFooter from './components/siteFooter.vue'
// lista compèonenti 
export default {
  name: 'App',
  components: {
    siteHeader,
    siteMain,
    siteFooter
  }
}
</script>

<style lang="scss">
  // impostazioni di reset
  *{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
</style>
