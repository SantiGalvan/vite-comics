<script>
export default {
    name: 'AppHeader',
    data: () => ({
        links: [
            {
                text: 'Characters',
                url: '#',
                current: false,
            },
            {
                text: 'Comics',
                url: '#',
                current: true,
            },
            {
                text: 'Movies',
                url: '#',
                current: false,
            },
            {
                text: 'TV',
                url: '#',
                current: false,
            },
            {
                text: 'Games',
                url: '#',
                current: false,
            },
            {
                text: 'Collectibles',
                url: '#',
                current: false,
            },
            {
                text: 'Videos',
                url: '#',
                current: false,
            },
            {
                text: 'Fans',
                url: '#',
                current: false,
            },
            {
                text: 'News',
                url: '#',
                current: false,
            },
            {
                text: 'Shop',
                url: '#',
                current: false,
            },
        ]

    })
};
</script>

<template>
    <header>
        <div class="container header-elements">
            <figure>
                <a href="#">
                    <img src="../assets/img/dc-logo.png" alt="Logo DC">
                </a>
            </figure>
            <nav>
                <ul class="header-list">
                    <li v-for="(link, i) in links" :key="i"><a :href="`${link.url}`">{{ link.text }}</a></li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<style scoped>
.header-elements {
    height: 120px;

    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav,
ul,
li {
    height: 100%;
}

a {
    color: black;
    height: 100%;
}

.header-list {
    display: flex;
    align-items: center;
    gap: 20px;
    text-transform: uppercase;
    font-size: 0.9rem;
}

.header-list li a {
    display: flex;
    align-items: center;
}

img {
    height: 80px;
}

.active {
    border-bottom: 4px solid #0282f9;
}

.active a {
    color: #0282f9;
}

li:hover {
    border-bottom: 4px solid #0282f9;
}

li:hover a {
    color: #0282f9;
}
</style>