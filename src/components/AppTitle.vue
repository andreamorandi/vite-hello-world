<script>
    export default {
        data() {
            return {
                name: "AppTitle",
                title: "La mia prima app con Vite!"
            }
        }
    }
</script>

<template>
    <h1>{{ title }}</h1>
</template>

<style scoped>
    h1 {
        margin-bottom: 4rem;
    }
</style>