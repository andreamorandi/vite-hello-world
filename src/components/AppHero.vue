<script>
    export default {
        data() {
            return {
                jumboImg: 'nature.webp'
            }
        },
        methods: {
            getImagePath() {
                return new URL(`../assets/img/${this.jumboImg}`, import.meta.url).href;
            }
        }
    }
</script>

<template>
    <div class="jumbotron">
        <img :src="getImagePath()" alt="Nature">
    </div>
</template>

<style scoped>
    .jumbotron img {
        width: 100%;
        object-fit: cover;
    }
</style>