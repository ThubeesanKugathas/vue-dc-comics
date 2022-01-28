<template>
    <header id="app">
        <header-box-nav :navbar="nav"/>
        <div class="ms_jumbotron"></div>
    </header>
</template>

<script>
import HeaderBoxNav from './HeaderBoxNav.vue'

export default {
    name: 'App',
    components: {
        HeaderBoxNav,
    },
    props: {
        nav: Array
    }
}
</script>

<style lang="scss" scoped>
    .ms_jumbotron {
        height: 400px;
        background: url(../assets/jumbotron.jpg) no-repeat;
        background-size: cover;
    }
</style>