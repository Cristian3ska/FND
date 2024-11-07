<template>
    <div>
        <Header />
        <HomeContent />
        <Footer />
    </div>
</template>

<script>
    import Header from './components/header.vue';
    import Footer from './components/Footer.vue';
    import HomeContent from './components/homecontent.vue';
    
    export default {
        components: {
        Header,
        Footer,
        HomeContent
        }
    };
    </script>
    
    <style>
    body {
        background-color: #231f20;
        color: #fff;
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
    }
</style>
