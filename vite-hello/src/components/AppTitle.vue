<script>
export default {
    name: 'main-title',
    data() {
        return {
            titolo: 'La mia prima App con vite!'
        }
    }
}
</script>

<template>
    <h1>{{ titolo }}</h1>
</template>

<style>
h1 {
    color: bisque;
}
</style>