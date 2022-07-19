<template>
  <div id="app">

    <!-- header -->
    <HeaderComponent />

    <!-- main -->
    <MainComponent />

    <!-- footer -->
    <FooterComponent />
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import MainComponent from './components/MainComponent.vue'
import FooterComponent from './components/FooterComponent.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    MainComponent,
    FooterComponent
  }  
}
</script>

<style lang="scss">
@import '@/style/common';
@import '@/style/variables';
</style>
