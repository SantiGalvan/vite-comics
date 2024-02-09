<script>
import MainLinks from './MainLinks.vue';
import DcCard from './DcCard.vue';

export default {
    name: 'AppMain',
    components: { MainLinks, DcCard },
    props: {
        books: Array
    }
}
</script>

<template>
    <main>

        <!-- Section Content -->
        <section id="section-content">
            <div class="container container-card">
                <DcCard v-for="(book, i) in books" :key="i" :image="book.thumb" :title="book.series" />
            </div>
        </section>

        <!-- Section Links -->
        <MainLinks />
    </main>
</template>

<style lang="scss" scoped>
main {
    background-color: black;
}

#section-content {
    text-align: center;
}

.container-card {
    display: flex;
    flex-wrap: wrap;
    padding-top: 40px;
    margin-bottom: 40px;

    .dc-card {
        flex-basis: calc(100% / 6);
        cursor: pointer;

        &:hover {
            scale: 1.1;
        }
    }
}

h2 {
    color: #fff;
    line-height: 150px;
}
</style>