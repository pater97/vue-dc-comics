<template>
  <div id="app">
    <!-- header -->
    <header id="site_header">
      <siteHeader/>
    </header>
    <!-- main -->
    <main id="main_site">

    </main>
    <!-- footer -->
    <footer id="site_footer">

    </footer>
  </div>
</template>

<script>
import siteHeader from './components/siteHeader.vue'

export default {
  name: 'App',
  components: {
    siteHeader
  }
}
</script>

<style lang="scss">
#app {
  
}
</style>
