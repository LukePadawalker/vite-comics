<script setup>
import { ref } from 'vue'

defineProps({
    msg: String,
})

const count = ref(0)
</script>

<template>
    <div class="container">
        <img src="/src/assets/img/dc-logo.png" alt="">
        <ul class="header-menu">
            <li> <a href="">Characters</a></li>
            <li> <a href="">Characters</a></li>
            <li> <a href="">Characters</a></li>

        </ul>

    </div>
</template>

<style lang="scss" scoped>
.container {
    height: 100px;
    width: 100%;
    display: flex;
    justify-content: space-around;
    background-color: white;

    .header-menu {
        display: flex;
    }
}
</style>
