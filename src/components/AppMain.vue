<script>
import MainLinks from './MainLinks.vue';

export default {
    name: 'AppMain',
    components: { MainLinks }
}
</script>

<template>
    <main>

        <!-- Section Content -->
        <section id="section-content" class="container">
            <h2> Content goes here </h2>
        </section>

        <!-- Section Links -->
        <MainLinks />
    </main>
</template>

<style scoped>
main {
    background-color: black;
}

#section-content {
    text-align: center;
    height: 150px;
}

h2 {
    color: #fff;
    line-height: 150px;
}
</style>