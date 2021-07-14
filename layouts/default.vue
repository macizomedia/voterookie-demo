<template>
    <i-layout>
        <i-layout-header>
            <Header />
        </i-layout-header>

        <i-layout-content>
            <Nuxt />
        </i-layout-content>

        <i-layout-footer>
            <Footer />
        </i-layout-footer>
    </i-layout>
</template>
<script>
import Footer from '../components/Footer.vue'
import Header from '../components/Header.vue'

export default {
    components: {
        Header,
        Footer,
    },
}
</script>

<style>

</style>
