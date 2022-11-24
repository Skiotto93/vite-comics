<script setup>

</script>

<template>
    <!--I Sezione-->
    <section class="I-section">
        <div class="container">
            <h3><a href="#">Content Goes Here</a></h3>
        </div>
    </section>
    <!--II Sezione-->
    <section class="II-section">
        <div class="container d-flex">
            <div class="card pl-3">
                <img src="../assets/buy-comics-digital-comics.png" alt="#">
                <span>DIGITAL COMICS</span>
            </div>
            <div class="card">
                <img src="../assets/buy-comics-merchandise.png" alt="#">
                <span>DC MERCHANDISE</span>
            </div>
            <div class="card">
                <img src="../assets/buy-comics-subscriptions.png" alt="#">
                <span>SUBSCRIPTION</span>
            </div>
            <div class="card">
                <img src="../assets/buy-comics-shop-locator.png" alt="#">
                <span>COMIC SHOP LOCATOR</span>
            </div>
            <div class="card pr-3">
                <img src="../assets/buy-dc-power-visa.svg" alt="#">
                <span>DC POWER VISA</span>
            </div>
        </div>
    </section>
</template>

<style scoped>
.I-section {
    background-color: #1c1c1c;
}
.container {
    max-width: 1200px;
    margin: auto;
    padding: 50px 0px;
}
.d-flex{
    display: flex;
    justify-content: space-between;
}
a {
    color: #fff;
    text-decoration: none;
    cursor: pointer;
}
.II-section {
    background-color: #0282f9;
}
.pl-3 {
    padding-left: 20px;
}
.pr-3 {
    padding-right: 20px;
}
.card {
    color: #fff;
    display: flex;
    align-items: center;
}
img {
    height: 60px;
}
span {
    padding: 0 20px;
    font-size: 14px;
}
</style>