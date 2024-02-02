<script setup>
import dcFilms from '/src/assets/data/dc-comics.js';
import AppButton from './AppButton.vue'
</script>

<template>
    <div id="root">
        <div class="container">

            <div class="card" v-for="film in dcFilms">
                <div class="img-card">
                    <img :src="film.thumb" alt="">
                </div>
                <p>ACTION COMICS</p>
            </div>

            <AppButton />
        </div>

    </div>
</template>

<style lang="scss" scoped>
#root {
    width: 100%;
    background-color: rgb(29, 28, 28);
    position: relative;
    z-index: 1;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 700px;

    .container {
        width: 75%;
        display: flex;
        justify-content: space-evenly;
        gap: 10px;
        align-items: center;
        flex-wrap: wrap;

        .card {
            width: calc(100% / 6 - 20px);
            height: 250px;

            .img-card {
                width: 100%;
                height: 180px;



                img {
                    width: 100%;
                    height: 100%;
                }
            }


            p {
                width: 100%;
                color: white;
                font-size: 0.7rem;
                padding-top: 1rem;
            }

        }


    }
}
</style>
