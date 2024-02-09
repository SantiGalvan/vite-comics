<script>
import MainLinks from './MainLinks.vue';
import DcCard from './DcCard.vue';

export default {
    name: 'AppMain',
    components: { MainLinks, DcCard }
}
</script>

<template>
    <main>

        <!-- Section Content -->
        <section id="section-content">
            <div class="container">
                <DcCard />
            </div>
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