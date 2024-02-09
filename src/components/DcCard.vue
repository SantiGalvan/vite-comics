<script>
export default {
    name: 'AppContent',
    props: {
        image: String,
        title: String
    }
}
</script>

<template>
    <div class="dc-card">
        <figure>
            <img :src="image" :alt="title">
        </figure>
        <h3>{{ title }}</h3>
    </div>
</template>

<style scoped>
.dc-card {
    padding: 10px;
}

figure {
    height: 280px;
    overflow: hidden;
}

img {
    display: block;
    height: 100%;
}

h3 {
    color: #fff;
    margin-top: 10px;
}
</style>