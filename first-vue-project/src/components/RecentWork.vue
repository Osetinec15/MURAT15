<template>
    <div class="resent-work">
        <h2>Recent Work</h2>
        <div class="border"></div>
        <div class="blog-container">
            <div class="blog">
                <img src="../assets/Image.png">
                <a class="border_2" href="#">read more +</a>
                <h3>Project One</h3>
                <p>Donec id elit non mi porta gravida at eget metus. Fusce dapibus, justo sit amet risus etiam porta sem.</p>
            </div>

            <div class="blog">
                <img src="../assets/Image.png">
                <a class="border_2" href="#">read more +</a>
                <h3>Project Two</h3>
                <p>Donec id elit non mi porta gravida at eget metus. Fusce dapibus, justo sit amet risus etiam porta sem.</p>
            </div>

            <div class="blog">
                <img src="../assets/Image.png">
                <a class="border_2" href="#">read more +</a>
                <h3>Project Three</h3>
                <p>Donec id elit non mi porta gravida at eget metus. Fusce dapibus, justo sit amet risus etiam porta sem.</p>
            </div>

            <div class="blog">
                <img src="../assets/Image.png">
                <a class="border_2" href="#">read more +</a>
                <h3>Project Four</h3>
                <p>Donec id elit non mi porta gravida at eget metus. Fusce dapibus, justo sit amet risus etiam porta sem.</p>
            </div>

        </div>
    </div>
</template>

<script>
    export default {
        name: "RecentWork"
    }
</script>

<style lang="scss" scoped>
.resent-work{
    margin-top: 80px;
    margin-left: 212px;
}
.border{
    border-bottom: #7dc945 solid 2px;
    width: 140px;
    height: 2px
}
    h2{
        width: 140px;
        height: 17px;
        color: #585f69;
        font-family: "Open Sans";
        font-size: 22px;
        font-weight: 400;
        line-height: 36px;
    }

    .blog-container{
        margin-top: 25px;
        display: flex;
    }
    .blog{
        width: 265px;
        height: 240px;
        margin-right: 56px;
    }
    a{
        text-decoration: none;
        width: 70px;
        height: 9px;
        color: #ffffff;
        font-family:"Open Sans";
        font-size: 13px;
        font-weight: 400;
        line-height: 36px;
        position: relative;
        bottom: 56px;
        left: 190px;
        padding: 3px;
    }
    .border_2{
        width: 85px;
        height: 25px;
        background-color: #7dc945
    }
    img{
        width: 248px;
        height: 149px;
    }
    h3{
        margin-top: -25px;
        width: 130px;
        height: 20px;
        color: #585f69;
        font-family: "Open Sans";
        font-size: 20px;
        font-weight: 400;
        line-height: 36px;
    }

    p {
        width: 240px;
        height: 50px;
        color: #585f69;
        font-family: "Open Sans";
        font-size: 13px;
        font-weight: 400;
        line-height: 19px;
    }
</style>