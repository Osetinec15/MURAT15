<template>
    <div class="base-footer">
        <p>
            2014 © ALL Rights Reserved. Unify Theme by  <span>Htmlstream</span>  |  <span>Privacy Policy</span>  |  <span>Terms of Service</span>
        </p>
       <a href="#"><img src="../assets/footer-image.png"></a>
    </div>
</template>

<script>
    export default {
        name: "BaseFooter"
    }
</script>

<style lang="scss" scoped>
.base-footer{
    width: 1600px;
    height: 65px;
    background-color: #535a65;
    display: flex;
}
    p {
        width: 540px;
        height: 12px;
        color: #e4e4e4;
        font-family: "Open Sans";
        font-size: 12px;
        font-weight: 400;
        line-height: 18px;
        margin-top: 20px;
        margin-left: 212px;
    }
    
    span{
        color: #7dc945;
    }
    img{
        width: 103px;
        height: 39px;
        margin-top: 14px;
        margin-left: 525px;
    }
</style>