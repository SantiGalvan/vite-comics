<script>
import AppHeader from './components/AppHeader.vue'
export default {
    name: 'AppComics',
    components: {
        AppHeader
    }
};
</script>

<template>
    <AppHeader />
</template>

<style>
/* Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Generics */
.container {
    max-width: 1200px;
    margin: 0 auto;
}
</style>