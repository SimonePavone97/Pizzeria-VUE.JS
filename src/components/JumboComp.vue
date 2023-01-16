<template>
    <div class="hero-image mt-2
    mb-4">
        <div class="hero-text">
            <h1 style="font-size:75px">La vera pizza italiana</h1>
            <span class="fw-bold" style="font-size:20px">
                <mark> Ingredienti di prima qualità, freschi e a km 0 con una farina di qualità. Questi
                    sono gli elementi che danno vita ad una pizza leggera, genuina, come tradizione comanda!
                </mark>
            </span>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'JumboComp',

    }
</script>

<style scoped lang="scss">
    .hero-image {
        background-image: url("../assets/Mozzarella.jpg");
        background-color: #cccccc;
        height: 550px;
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        position: relative;
    }

    .hero-text {
        text-align: center;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        color: white;
    }
</style>