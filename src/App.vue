<template>
    <div id="app">
        <app-nav-bar/>
        <router-view/>
    </div>
</template>

<script>

    import AppNavBar from "./components/AppNavBar";

    export default {
        name: 'App',
        components: {
            AppNavBar
        },
    }
</script>

<style>
</style>
