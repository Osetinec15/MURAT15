<template>
    <div class="our-clients">
        <div class="header">
            <h2>Our Clients</h2>
            <div class="border"></div>
        </div>
        <div class="flex">
        <img src="../assets/clients-image.png">
        <img src="../assets/clients-image.png">
        <img src="../assets/clients-image.png">
        <img src="../assets/clients-image.png">
        <img src="../assets/clients-image.png">
        <img src="../assets/clients-image.png">
        <img src="../assets/clients-image.png">
        <img src="../assets/clients-image.png">
        </div>
    </div>
</template>

<script>
    export default {
        name: "OurClients"
    }
</script>

<style lang="scss" scoped>

    .border{
        border-bottom: #7dc945 solid 2px;
        width: 186px;
        height: 2px
    }
    .header{
     margin-left: 212px;
    }
    .flex{
        display: flex;
        margin-left: 212px;
        margin-top: 28px;
    }
    img {
        width: 144px;
        height: 144px;
        padding-right:9px;
    }
</style>