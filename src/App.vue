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
body {
    font-family: "Open Sans", sans-serif;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
}

ul {
    list-style-type: none;
}

li a {
    text-decoration: none;
}

img {
    max-width: 100%;
    height: auto;
}
</style>