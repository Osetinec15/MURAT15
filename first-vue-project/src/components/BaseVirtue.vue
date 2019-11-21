<template>
    <div class="base-virtue">
        <div class="first-block">
            <img src="../assets/Icon_in.png">
            <h3>Fully Responsive</h3>
            <p>Donec id elit non mi porta gravida at eget
                metus. Fusce dapibus, tellus ac cursus
                commodo, tortor mauris condimentum
                nibh, ut fermentum massa justo sit amet
                risus etiam sem...</p>
        </div>

        <div class="second-block">
            <img src="../assets/hexagon.png">
            <h3>HTML5 + CSS3</h3>
            <p>Donec id elit non mi porta gravida at eget
                metus. Fusce dapibus, tellus ac cursus
                commodo, tortor mauris condimentum
                nibh, ut fermentum massa justo sit amet
                risus etiam sem...</p>
        </div>

        <div class="third-block">
            <img src="../assets/rocket.png">
            <h3>Launch Ready</h3>
            <p>Donec id elit non mi porta gravida at eget
                metus. Fusce dapibus, tellus ac cursus
                commodo, tortor mauris condimentum
                nibh, ut fermentum massa justo sit amet
                risus etiam sem...</p>
        </div>

    </div>
</template>

<script>
    export default {
        name: "BaseVirtue"
    }
</script>

<style lang="scss" scoped>
    .base-virtue{
        width: 1600px;
        display: flex;

    }

    .first-block{
        width: 337px;
        height: 168px;
        margin-left: 212px;

    }

    .second-block{
        width: 337px;
        height: 168px;
        margin-left: 128px;
    }


    .third-block{
        width: 337px;
        height: 168px;
        margin-left: 158px;
    }



    img {
       width: 30px;
        height: 30px;
        position: relative;
        top: 63px;
        right: 55px;
    }


    p {
        width: 241px;
        height: 85px;
        color: #555555;
        font-family: "Helvetica Neue";
        font-size: 13px;
        font-weight: 400;
        line-height: 19px;
    }

    h3 {
        color: #585f69;
        font-family: "Open Sans";
        font-size: 22px;
        font-weight: 400;
        line-height: 36px;
        text-transform: uppercase;
    }

    @font-face {
        font-family: "Font Awesome";
        src: url("../../fonts/font-awesome-4.7.0/fonts/fontawesome-webfont.svg");
    }
</style>