<template>
  <div id="app">

    <!-- header -->
    <HeaderComponent />

    <!-- main -->
    <MainComponent />
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import MainComponent from './components/MainComponent.vue'


export default {
  name: 'App',
  components: {
    HeaderComponent,
    MainComponent
  },
  
}
</script>

<style lang="scss">
@import '@/style/common';
@import '@/style/variables';
</style>
