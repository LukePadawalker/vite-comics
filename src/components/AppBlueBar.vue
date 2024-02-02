<script setup>

</script>

<template>
    <div id="root">
        <div class="container">
            <div class="card">
                <img src="/src/assets/img/buy-comics-digital-comics.png" alt="">
                <p>DIGITAL COMICS</p>
            </div>
            <div class="card">
                <img src="/src/assets/img/buy-comics-merchandise.png" alt="">
                <p>DC MERCHANDISE</p>
            </div>
            <div class="card">
                <img src="/src/assets/img/buy-comics-subscriptions.png" alt="">
                <p>SUBSCRIPTION</p>
            </div>
            <div class="card">
                <img src="/src/assets/img/buy-comics-shop-locator.png" alt="">
                <p>COMIC SHOP LOCATOR</p>
            </div>
            <div class="card">
                <img src="/src/assets/img/buy-dc-power-visa.svg" alt="">
                <p>DC POWER VISA</p>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
#root {
    background-color: rgb(0, 136, 255);
    width: 100%;
    height: 150px;
    position: relative;
    z-index: 1;

    .container {
        width: 75%;
        height: 100%;
        margin: 0 auto;
        padding: 2rem;
        display: flex;
        justify-content: space-around;
        align-items: center;

        .card {
            display: flex;
            align-items: center;
            gap: 10px;

            img {
                max-height: 50px;
            }

            p {
                font-size: 0.5rem;
                color: white;
            }
        }

    }
}
</style>
