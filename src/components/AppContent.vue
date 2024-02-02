<script setup>
</script>

<template>
    <div id="root">
        <div class="container">
            <div class="card"></div>

        </div>

    </div>
</template>

<style lang="scss" scoped>
#root {
    width: 100%;
    background-color: rgb(20, 20, 20);
    position: relative;
    z-index: 1;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 130px;

    .container {
        width: 75%;
        display: flex;
        justify-content: center;
        align-items: center;

        p {
            width: 100%;
            color: white;
        }
    }
}
</style>
