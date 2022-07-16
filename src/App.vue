<template>
  <div id="app">
  <MainHeader />
  <MainContent />
  <BlueBand />
  <MainFooter />
  </div>
</template>

<script>
import MainHeader from './components/Header.vue'
import MainContent from './components/Main.vue'
import MainFooter from './components/Footer.vue'
import BlueBand from './components/BlueBand.vue'

export default {
  name: 'App',
  components: {
    MainHeader,
    MainContent,
    MainFooter,
    BlueBand,
  }
}
</script>


<style lang="scss">


@import'~bootstrap/dist/css/bootstrap.css'

</style>
