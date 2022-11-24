<script setup>

</script>

<template>
    <div class="headerContainer">
        <div class="logo">
            <img src="../assets/dc-logo.png" alt="logo">
        </div>
        <div class="header-nav">
            <nav>
                <ul>
                    <li><a href="#">CHARACTERS</a></li>
                    <li><a href="#">COMICS</a></li>
                    <li><a href="#">MOVIES</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">GAMES</a></li>
                    <li><a href="#">COLLECTIBLES</a></li>
                    <li><a href="#">VIDEOS</a></li>
                    <li><a href="#">FANS</a></li>
                    <li><a href="#">NEWS</a></li>
                    <li><a href="#">SHOP</a></li>
                </ul>
            </nav>
        </div>
    </div>
</template>

<style scoped>
.headerContainer {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin: auto;
    max-width: 75rem;
    padding: 10px 0;
}
nav ul {
    display: flex;
}
nav ul li {
    list-style: none;
    padding-left: 1.25rem;
}
a {
    text-decoration: none;
    color: #000;
    cursor: pointer;
    font-weight: bold;
    font-size: 14px;
}
img {
    max-height: 80px
}
</style>
