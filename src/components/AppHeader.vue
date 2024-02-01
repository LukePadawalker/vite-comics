<script setup>
import { ref } from 'vue'

const count = ref(0)
</script>

<template>
    <div>
        <div class="container">
            <img src="/src/assets/img/dc-logo.png" alt="">
            <ul class="header-menu">
                <li> <a href="">Characters</a></li>
                <li> <a href="">Characters</a></li>
                <li> <a href="">Characters</a></li>
            </ul>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.container {
    height: 100px;
    width: 75%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    background-color: white;

    .header-menu {
        display: flex;
    }
}
</style>
