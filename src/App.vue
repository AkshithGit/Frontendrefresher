<template>
    <div id="container">
        <Header title="My Cool App" action="Get started"/>
    </div>
    <div id="container">
        <Header title="Your app" action="Cool"/>
    </div>

</template>

<script>
export default {
    name: 'App',
    components: {
        Header
    }
}
import Header from './Header.vue'
</script>

<style>
#app {
    text-align: center;
    color: yellowgreen;
    margin-top: 60px;
}
#container {
    border: 1px solid steelblue;
    padding: 30px;
    max-width: 500px;
    margin: 20px auto;
}

button {
    padding: 10px 20px;
    font-size: 15px;
    background: seagreen;
    color: white;
    border-radius: 5px;
    cursor: pointer;
}


</style>
