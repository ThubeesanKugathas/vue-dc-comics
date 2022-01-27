<template>
    <footer id="app">
        <footer-box-top />
        <footer-box-middle />
        <footer-box-bottom />
    </footer>
</template>

<script>
import FooterBoxTop from './FooterBoxTop.vue'
import FooterBoxMiddle from './FooterBoxMiddle.vue'
import FooterBoxBottom from './FooterBoxBottom.vue'

export default {
    name: 'app',
    components: {
        FooterBoxTop,
        FooterBoxMiddle,
        FooterBoxBottom
    }
}
</script>

<style lang="scss" scoped>

</style>