<template>
    <div class="logos-wrapper">
        <h2>Find Best Logos</h2>
        <div class="items-logos">
            <img src="../assets/logo/vue.png" alt="">
        </div>
        <div class="items-logos">
            <img src="../assets/logo/react.png" alt="">
        </div>
        <div class="items-logos">
            <img src="../assets/logo/laravel.png" alt="">
        </div>
        <div class="items-logos">
            <img src="../assets/logo/django.png" alt="">
        </div>
        <div class="items-logos">
            <img src="../assets/logo/git.png" alt="">
        </div>
        <div class="items-logos">
            <img src="../assets/logo/vue.png" alt="">
        </div>
        <div class="items-logos">
            <img src="../assets/logo/react.png" alt="">
        </div>
        <div class="items-logos">
            <img src="../assets/logo/laravel.png" alt="">
        </div>
        <div class="items-logos">
            <img src="../assets/logo/django.png" alt="">
        </div>
        <div class="items-logos">
            <img src="../assets/logo/git.png" alt="">
        </div>
        <div class="items-logos">
            <img src="" alt="">
        </div>
        
    </div>
</template>
<script>
export default {
    name:'Logos'
}
</script>
<style scoped>
    .logos-wrapper{
        width: 80%;
        overflow: hidden;
        margin: auto;
        background-color: blue;
    }

    .items-logos{
        background-color: brown;
        width: 100px;
        /* height: 10px; */
        float: left;
    }

    .items-logos img{
        width: 150px;
        height: 150px;
    }

</style>