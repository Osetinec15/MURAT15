<template>
    <div class="nav-bar">
        <img  src="../assets/logo.png">
          <div>
            <a>LANGUGAES|HELP|LOGIN</a>
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
    a{
        width: 189px;
        height: 13px;
        color: #9b9b9b;
        font-family: "Helvetica Neue";
        font-size: 12px;
        font-weight: 400;
        line-height: 24px;
        text-transform: uppercase;
        margin-left: 875px;
    }
    .search{
        width: 43px;
        height: 46px;
        color: #b8b8b8;
        font-family: "Font Awesome";
        font-size: 15px;
        font-weight: 400;
        line-height: 30.66px;
        margin-left: -60px;
    }




</style>