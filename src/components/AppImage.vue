<template>
    <div>
        <img :src="getImagePath(imagePath)" alt="">
    </div>
</template>

<script>
export default {
    data() {
        return {
            imagePath: "vue.svg"
        }
    },
    methods: {
        getImagePath(img) {
            return new URL(`../assets/${img}`, import.meta.url).href;
        }
    }
}
</script>

<style>
    img {
        max-width: 100px;
    }

    div {
        padding: 20px;
    }
</style>