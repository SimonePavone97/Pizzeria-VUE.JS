<template>
    <div class="container padd" id="C4">

        <h1 class="pb-3">Ecco le nostre golosissime pizze <span>&#127829;</span> <span>&#129316;</span> </h1>

        <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
            <div class="carousel-indicators">
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active"
                    aria-current="true" aria-label="Slide 1"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1"
                    aria-label="Slide 2"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2"
                    aria-label="Slide 3"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="3"
                    aria-label="Slide 4"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="4"
                    aria-label="Slide 5"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="5"
                    aria-label="Slide 6"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="6"
                    aria-label="Slide 7"></button>
            </div>
            <div class="carousel-inner hei">
                <div class="carousel-item active">
                    <img src="../assets/Pizze/pizza1.jpg" class="d-block w-100 img-fluid" alt="Anime">
                </div>
                <div class="carousel-item">
                    <img src="../assets/Pizze/pizza2.jpg" class="d-block w-100 img-fluid" alt="Anime">
                </div>
                <div class="carousel-item">
                    <img src="../assets/Pizze/pizza3.jpg" class="d-block w-100 img-fluid" alt="Anime">
                </div>
                <div class="carousel-item">
                    <img src="../assets/Pizze/pizza4.jpg" class="d-block w-100 img-fluid" alt="Anime">
                </div>
                <div class="carousel-item">
                    <img src="../assets/Pizze/pizza5.jpg" class="d-block w-100 img-fluid" alt="Anime">
                </div>
                <div class="carousel-item">
                    <img src="../assets/Pizze/pizza6.jpg" class="d-block w-100 img-fluid" alt="Anime">
                </div>
                <div class="carousel-item">
                    <img src="../assets/Pizze/pizza7.jpg" class="d-block w-100 img-fluid" alt="Anime">
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators"
                data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators"
                data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>
    </div>

</template>

<script>
    export default {
        name: 'ImgComp',

    }
</script>

<style scoped lang="scss">
    .padd {
        padding-top: 60px;
        padding-bottom: 60px;
    }


</style>