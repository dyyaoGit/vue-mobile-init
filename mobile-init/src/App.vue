<template>
    <div id="app">
        <router-view/>
    </div>
</template>

<script>
    export default {
        name: 'app'
    }
</script>

<style>
    @import './styles/init.css';
    #app {
        max-width: 750px;
        margin: 0 auto;
    }
</style>
