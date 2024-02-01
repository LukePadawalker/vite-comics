<script setup>
import { ref } from 'vue'

const array = 'data.js';

const count = ref(0)
</script>

<template>
    <div>
        <div class="container">
            <img src="/src/assets/img/dc-logo.png" alt="">
            <ul class="header-menu">
                <li v-for="voice in array">
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

        li {
            a {
                color: rgb(65, 63, 63)
            }
        }

    }

}
</style>
