<template>
    <header>
        <h1>
            {{ title }}
        </h1>
        <button>
            {{ action }}
        </button>
    </header>
</template>

<script>
export default {
    name: 'Header',
    props: {
        title: String,
        action: String
    }
}
</script>

<style>

</style>
