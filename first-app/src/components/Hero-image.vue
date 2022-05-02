<template>
    <div class="hero-img">
        <h2 class="hero-title">Benvenuto in Vue</h2>
        <img src="@/assets/heroimage.jpg" alt="">
    </div>
</template>

<style>
    .hero-title{
        max-width: 400px;
        margin: 2rem auto;
        font-size: 2.5rem;
        background-color: aquamarine;
    }
    .hero-img > img {
        width: 800px;
        object-fit: contain;
        margin: 1rem auto;
    }
</style>