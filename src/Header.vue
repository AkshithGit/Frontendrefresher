<template>
    <header>
        <h1 :style="{ color:colorpara }">
            {{ title }}
        </h1>
        <button @click="handleClick()" :style="{ background: bgcolor }">
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
    },
    methods: {
    handleClick() {
        console.log("button Clicked")
    }
}
}
</script>

<style>
h1 {
    color: yellowgreen;
}
</style>
