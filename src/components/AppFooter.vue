<script>
export default {
    name: 'AppFooter'
}
</script>

<template>
    <footer>
        <div class="upper-footer">
            <div class="container footer-container">
                <nav>
                    <div class="col">
                        <h4>Dc comics</h4>
                        <ul>
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">News</a></li>
                        </ul>
                        <h4>Shop</h4>
                        <ul>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collectibles</a></li>
                        </ul>
                    </div>
                    <div class="col">
                        <h4>Dc</h4>
                        <ul>
                            <li><a href="#">Therms of use</a></li>
                            <li><a href="#">Privacy policy (NEW)</a></li>
                            <li><a href="#">Add Choise</a></li>
                            <li><a href="#">Advertising</a></li>
                            <li><a href="#">Jobs</a></li>
                            <li><a href="#">Subscriptions</a></li>
                            <li><a href="#">Talent Workshops</a></li>
                            <li><a href="#">CPSC Certification</a></li>
                            <li><a href="#">Ratings</a></li>
                            <li><a href="#">Shop Help</a></li>
                            <li><a href="#">Contact Us</a></li>
                        </ul>
                    </div>
                    <div class="col">
                        <h4>Dc comics</h4>
                        <ul>
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">News</a></li>
                        </ul>
                    </div>
                </nav>
                <div class="logo-bg"></div>
            </div>
        </div>
        <div class="bottom-footer">
            <div class="container footer-container">
                <div class="actions">
                    <button>Sign-up now!</button>
                </div>
                <div class="follow">
                    <h2>Follow us</h2>
                    <figure>
                        <a href="https://www.facebook.com/?locale=it_IT" target="_blank">
                            <img src="../assets/img/footer-facebook.png" alt="Facebook">
                        </a>
                        <a href="https://twitter.com/?lang=it" target="_blank">
                            <img src="../assets/img/footer-twitter.png" alt="Twitter">
                        </a>
                        <a href="https://www.youtube.com/" target="_blank">
                            <img src="../assets/img/footer-youtube.png" alt="YouTube">
                        </a>
                        <a href="https://www.pinterest.it/" target="_blank">
                            <img src="../assets/img/footer-pinterest.png" alt="Pinterest">
                        </a>
                        <a href="https://www.pscp.tv/" target="_blank">
                            <img src="../assets/img/footer-periscope.png" alt="Periscope">
                        </a>
                    </figure>
                </div>
            </div>
        </div>
    </footer>
</template>

<style scoped>
.upper-footer {
    background-image: url(../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
}

.bottom-footer {
    background-color: #303030;
}

.footer-container {
    display: flex;
    justify-content: space-between;
    align-items: start;
}

nav {
    display: flex;
    padding-top: 20px;
    gap: 20px
}

li a {
    color: gray;
    font-size: 0.8rem;
}

.col {
    flex-basis: calc(100% / 3);
    margin-bottom: 50px;
}

h4 {
    color: #fff;
    text-transform: uppercase;
    margin: 20px 0;
}

.logo-bg {
    background-image: url(../assets/img/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-size: 500px;
    background-position: center;

    flex-basis: 50%;
    align-self: stretch;
}

.actions {
    min-height: 100px;
    display: flex;
    align-items: center;
}

button {
    padding: 10px 15px;
    background-color: transparent;
    border-color: #0282f9;
    text-transform: uppercase;
    color: #fff;
    font-size: 1.1rem;
    cursor: pointer;
}

.follow {
    min-height: 100px;
    color: #0282f9;
    text-transform: uppercase;

    display: flex;
    align-items: center;
    gap: 20px;
}

figure img {
    margin: 0 10px;
}
</style>