<template>
    <div class="container pb-4" id="C5">
        <l-map style="height: 500px" :zoom="zoom" :center="center">
            <l-tile-layer :url="url" :attribution="attribution"></l-tile-layer>
            <l-marker :lat-lng="markerLatLng">

                <l-Popup>
                    <div class="card text-center" style="width: auto;">
                        <img src="../assets/logo-arch.png" class="card-img-top img-fluid" alt="LogoPizzeria">
                        <div class="card-body">
                            <h3 class="card-title">Arch-Way</h3>
                            <p class="card-text">Ti aspettiamo nella nostra pizzeria. <br> Clicca il bottone di sotto per raggiungerci! 
                            </p>
                            <a href="https://goo.gl/maps/N5psp4TgfKAT9asaA" target="_blank" class="btn btn-primary">Vieni a trovarci! </a>
                        </div>
                    </div>

                </l-Popup>


            </l-marker>
        </l-map>
    </div>

</template>

<script>
    import {
        LMap,
        LTileLayer,
        LMarker,
        LPopup
    } from 'vue2-leaflet';

    export default {
        components: {
            LMap,
            LTileLayer,
            LMarker,
            LPopup
        },
        data() {
            return {
                url: 'https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png',
                attribution: '&copy; <a target="_blank" href="http://osm.org/copyright">OpenStreetMap</a> contributors',
                zoom: 15,
                center: [41.03081, 16.98683],
                markerLatLng: [41.03081, 16.98683]
            };
        }
    }
</script>


<style scoped lang="scss">

a{
    color: white!important;
    
};

</style>