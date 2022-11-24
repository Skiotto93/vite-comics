<script setup>

</script>

<template>
    <!--I Section-->
    <section class="I-section">
        <div class="container d-flex">
            <div class="col">
                <h4>DC COMICS</h4>
                <nav>
                    <ul>
                        <li><a href="#">Chatacters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">Tv</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Videos</a></li>
                        <li><a href="#">News</a></li>
                    </ul>
                </nav>
                <h4>SHOP</h4>
                <nav>
                    <ul>
                        <li><a href="#">Shop DC</a></li>
                        <li><a href="#">Shop DC Collectibles</a></li>
                    </ul>
                </nav>
            </div>
            <div class="col">
            <h4>DC</h4>
                <nav>
                    <ul>
                        <li><a href="#">Therms of Use</a></li>
                        <li><a href="#">Privacy Policy(New)</a></li>
                        <li><a href="#">Ad Choices</a></li>
                        <li><a href="#">Advertising</a></li>
                        <li><a href="#">Jobs</a></li>
                        <li><a href="#">Subscriptions</a></li>
                        <li><a href="#">Talent Workshops</a></li>
                        <li><a href="#">CPSC Certificates</a></li>
                        <li><a href="#">Ratings</a></li>
                        <li><a href="#">Shop Help</a></li>
                        <li><a href="#">Contact Us</a></li>
                    </ul>
                </nav>
            </div>
            <div class="col">
                <h4>SITES</h4>
                <nav>
                    <ul>
                        <li><a href="#">DC</a></li>
                        <li><a href="#">MAD Magazine</a></li>
                        <li><a href="#">DC Kids</a></li>
                        <li><a href="#">DC Universe</a></li>
                        <li><a href="#">DC Power Visa</a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </section>
    <!--II Section-->
    <section class="II-section">
        <div class="container d-space-between">
            <div class="btn">
                <button class="btn-sign-up">SIGN-UP-NOW!</button>
            </div>
            <div class="follow-us">
                <h4>FOLLOW US</h4>
                <div class="icon">
                    <img src="../assets/footer-facebook.png" alt="#">
                </div>
                <div class="icon">
                    <img src="../assets/footer-twitter.png" alt="#">
                </div>
                <div class="icon">
                    <img src="../assets/footer-youtube.png" alt="#">
                </div>
                <div class="icon">
                    <img src="../assets/footer-pinterest.png" alt="#">
                </div>
                <div class="icon">
                    <img src="../assets/footer-periscope.png" alt="#">
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.container {
    max-width: 1200px;
    margin: auto;
    padding: 39px 0px;
}
.d-flex {
    display: flex;
}
.I-section {
    background-image: url('../assets/footer-bg.jpg');
    background-repeat: no-repeat;
    background-size: 100%;
}
h4 {
    color: #fff;
    padding: 15px 0;
}
nav ul li {
    list-style: none;
}
a {
    text-decoration: none;
    color: #959595;
    font-size: 12px;
}
.col {
    height: 370px;
    width: 15%;
}
.II-section {
    background-color: #303030;
}
.btn-sign-up {
    background-color: inherit;
    color: #fff;
    padding: 10px;
    border: 2px solid #0282f9;
}
.d-space-between {
    display: flex;
    justify-content: space-between;
    align-items: center
}
.follow-us {
    display: flex;
    align-items: center
}
.follow-us img {
    margin: 0 10px;
}
.follow-us h4 {
    padding-right: 20px;
}
</style>