<template>
    <header>
        <h1 :style="{ color:colorpara }">
            {{ title }}
        </h1>
        <button :style="{ background: bgcolor }">
            {{ action }}
        </button>
    </header>
</template>

<script>
export default {
    name: 'Header',
    props: {
        title: String,
        action: String,
        colorpara: String,
        bgcolor: String
    } 
}
</script>

<style>
h1 {
    color: yellowgreen;
}
</style>
