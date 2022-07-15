<template>
  <div id="app">
  <MainHeader />
  <MainContent />
  </div>
</template>

<script>
import MainHeader from './components/Header.vue'
import MainContent from './components/Main.vue'
export default {
  name: 'App',
  components: {
    MainHeader,
    MainContent
  }
}
</script>


<style lang="scss">
#app {

}

@import'~bootstrap/dist/css/bootstrap.css'

</style>
