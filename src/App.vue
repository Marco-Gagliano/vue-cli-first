<template>
  <div id="app">
    <HeaderPage/>
    <MainPage/>
    <FooterPage/>
    <JumbotronPage/>
  </div>
</template>

<script>

import HeaderPage from './components/HeaderPage.vue'
import JumbotronPage from './components/JumbotronPage.vue'
import MainPage from './components/MainPage.vue'
import FooterPage from './components/FooterPage.vue'

export default {
  name: 'App',
  components: {
    HeaderPage,
    JumbotronPage,
    MainPage,
    FooterPage
  }
}
</script>

<style scoped>

</style>
