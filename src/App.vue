<template>
  <div id="app">
    <header-box />
    <main-box />
    <footer-box />
  </div>
</template>

<script>
  import HeaderBox from './components/HeaderBox.vue'
  import MainBox from './components/MainBox.vue'
  import FooterBox from './components/FooterBox.vue'


export default {
  name: 'App',
  components: {
    HeaderBox,
    MainBox,
    FooterBox,
  }
}
</script>

<style lang="scss">

</style>
