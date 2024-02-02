<script setup>
import headerVoices from '/src/assets/data/data.js';
</script>

<template>
    <div>
        <div class="container">
            <img src="/src/assets/img/dc-logo.png" alt="">
            <ul class="header-menu">
                <li v-for="voice in headerVoices">
                    <a href="">{{ voice.text }}</a>
                </li>
            </ul>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.container {
    padding: 1rem;
    height: 100px;
    width: 75%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    background-color: white;

    .header-menu {
        display: flex;
        gap: 10px;
        align-items: center;

        ul {
            display: flex;

            li {
                display: flex;
                align-items: center;

                a {
                    color: rgb(65, 63, 63);
                    font-size: 0.4rem;
                    font-weight: bolder;
                    text-transform: uppercase;
                }
            }
        }
    }

}
</style>
