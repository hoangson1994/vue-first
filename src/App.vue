<template>
    <div id="app" class="iEKYSP">
        <Header/>
        <router-view/>
    </div>
</template>

<script>
    import Header from "./components/Header";

    export default {
        components: {Header}
    }
</script>

<style>
    @import "assets/css/antd.css";
</style>
