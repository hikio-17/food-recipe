<template>
    <div>
        <header>
            <HeaderApp />
        </header>

        <main>
            <Home />
        </main>

        <footer>
            <FooterApp />
        </footer>
    </div>
</template>

<script>
    import HeaderApp from '@/components/HeaderApp.vue'
    import FooterApp from '@/components/FooterApp.vue'
    import Home from './Home.vue'

    export default {
    components: { HeaderApp, FooterApp, Home }
}
</script>

