<template>
  <div id="app">

    <!-- header -->
    <HeaderComponent />

  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent
  },
  
}
</script>

<style lang="scss">
@import '@/style/common';
@import '@/style/variables';
</style>
