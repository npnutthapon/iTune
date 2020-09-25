<template>
<div id="app">
    <iTune />
</div>
</template>

<script>
import iTune from './components/iTune.vue'
export default {
    name: 'App',
    components: {
        iTune

    }
}
</script>

<style>
#app {
    font-family: 'Athiti', sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}

body {
    background-image: url('https://cdn.discordapp.com/attachments/746260527235334237/758702542690582558/BG.jpg');
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}
</style>
