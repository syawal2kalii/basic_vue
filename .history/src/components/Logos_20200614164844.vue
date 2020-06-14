<template>
    <div class="logos-wrapper">
        <h2>Find Best Logos</h2>
        <div class="items-logos">
            <img src="../assets/logo/vue.png" alt="">
        </div>
        <div class="items-logos">
            <img src="" alt="">
        </div>
        <div class="items-logos">
            <img src="" alt="">
        </div>
        <div class="items-logos">
            <img src="" alt="">
        </div>
        <div class="items-logos">
            <img src="" alt="">
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
        width: 70%;
        overflow: hidden;
        margin: auto;
    }

    .items-logos{
        width: 150px;
        height: 150px;
        float: left;
        margin-right: 20px;
        margin-bottom: 20px;
    }

    .items-logos img{
        width: 100%;
        height: 100%;
    }

</style>