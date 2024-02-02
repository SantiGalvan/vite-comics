<script>
export default {
    name: 'MainLinks'
}
</script>

<template>
    <section id="section-links">
        <div class="container links-content">
            <div class="links-col">
                <a href="#">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="Digital comics">
                </a>
                <h4>Digital comics</h4>
            </div>
            <div class="links-col">
                <a href="#">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="Dc merchandise">
                </a>
                <h4>Dc merchandise</h4>
            </div>
            <div class="links-col">
                <a href="#">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="Subscriptions">
                </a>
                <h4>Subscriptions</h4>
            </div>
            <div class="links-col">
                <a href="#">
                    <img class="img-small" src="../assets/img/buy-comics-shop-locator.png" alt="Comic shop locator">
                </a>
                <h4>Comic shop locator</h4>
            </div>
            <div class="links-col">
                <a href="#">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="Dc power visa">
                </a>
                <h4>Dc power visa</h4>
            </div>
        </div>
    </section>
</template>

<style scoped>
#section-links {
    background-color: #0282f9;
}

.links-content {
    display: flex;
    justify-content: center;
    height: 150px;
    gap: 40px;
}

.links-col {
    display: flex;
    align-items: center;
    gap: 10px;
}

.links-col img {
    width: 50px;
}

.links-col img.img-small {
    width: 30px;
}

h4 {
    color: #fff;
    text-transform: uppercase;
}
</style>