<template>
    <div class="pdf">
        <h1 class="f-size pb-4">Scarica qui il nostro menù</h1>

        <a href="Menù Arch Way.pdf" download class="f-sizeMenu">
            <button class="btn btn-danger f-sizeMenu">
               Scarica qui il nostro menù 
            </button>
            
        </a>
    </div>
</template>

<script>
    export default {
        name: 'PdfComp',

    }
</script>

<style>

.f-size{
    font-size: 60px;
}

.f-sizeMenu{
    font-size: 25px;
}
</style>