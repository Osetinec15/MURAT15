<template>
    <div class="base-download">
        <div class="text-content">
    <p class="first-text">Unify is a clean and fully responsive incredible Template.</p>
    <p class="second-text">At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi vehicula sem ut volutpat. Ut non libero magna fusce condimentum eleifend enim a feugiat corrupti quos.</p>
        </div>
        <div>
            <img src="../assets/Icon.png">
        <button>Download Now</button>
        </div>
        </div>
</template>

<script>
    export default {
        name: "BaseDownload"
    }
</script>

<style lang="scss" scoped>
.base-download{
    height: 144px;
    border: 1px solid #d6d6d6;
    color: #FDFDFD;
    display: flex;

}

.text-content{


}

.first-text{
    width: 650px;
    height: 24px;
    color: #666666;
    font-family: "Open Sans";
    font-size: 24px;
    font-weight: 400;
    line-height: 24px;
    margin-left: 212px;
}
    .second-text{
        width: 740px;
        height: 49px;
        color: #555555;
        font-family: "Open Sans";
        font-size: 13px;
        font-weight: 400;
        line-height: 18px;
        margin-left: 212px;
    }

    button{
        width: 205px;
        height: 51px;
        background-color: #72c02c;
        color: white;
        margin-top: 44px;
        margin-left: 50px;

    }
    button text{

        color: #ffffff;
        font-family: "HelveticaNeueCyr ";
        font-size: 18px;
        font-weight: 400;
        line-height: 36px;
    }

    img{
        position: relative;
        top: 3px;
        left: 100px;
        width: 20px;
        height: 15px;
    }

    @font-face {
        font-family:HelveticaNeueCyr;
        src: url("../../fonts/HelveticaNeueCyr-Thin.ttf");
    }
</style>