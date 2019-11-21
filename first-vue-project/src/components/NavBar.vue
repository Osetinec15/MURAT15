<template>
    <div class="nav-bar">
       <a href="#"><img  src="../assets/logo.png"></a>
        <div>
            <p>LANGUGAES|HELP|LOGIN</p>
            <ul>
                <li>HOME</li>
                <li>PAGES</li>
                <li>FEATURES</li>
                <li>PORTFOLIO</li>
                <li>BLOG</li>
                <li>CONTACTS</li>
            </ul>
          </div>
        <img class="search" src="../assets/search.png">
    </div>
</template>

<script>
    export default {
        name: "NavBar"
    }
</script>

<style lang="scss" scoped>
.nav-bar{
    width: 100%;
    height: 89px;
    display: flex;

}
img{
    width: 103px;
    height: 39px;
    margin-top: 38px;
    margin-left: 213px;
    margin-right: 0;
    margin-bottom: 0;
    padding: 0;

}
ul{
    display: flex;
    margin-left:329px;
    margin-top: 30px;
    padding: 0;
}


li {
        list-style: none;
        height: 12px;
        color: #687074;
        font-family: "Myriad Pro";
        font-size: 14px;
        font-weight: 400;
        text-transform: uppercase;
        margin-right:45px;

}
    p{
        width: 189px;
        height: 13px;
        color: #9b9b9b;
        font-family: "Helvetica Neue";
        font-size: 12px;
        font-weight: 400;
        line-height: 24px;
        text-transform: uppercase;
        margin-left: 755px;
    }
    .search{
        width: 43px;
        height: 46px;
        color: #b8b8b8;
        font-family: "Font Awesome webfont";
        font-size: 15px;
        font-weight: 400;
        line-height: 30.66px;
        margin-left: -40px;
    }

    @font-face {
        font-family: "Myriad Pro";
        src: url("../../fonts/myriad-pro.otf");
    }

@font-face {
    font-family: "Font Awesome";
    src: url(../../fonts/font-awesome-4.7.0/fonts/fontawesome-webfont.svg);
}



</style>