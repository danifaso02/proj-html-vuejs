<script>
export default {
  name: "AppHeader",
};
</script>

<template>
    <div class="container">
        <div class="header-top">
            <span>Everything about Lifestyle, Travel and Gadgets!</span>
            <nav>
                <ul>
                    <li>SIGN IN</li>
                    <li>ABOUT US</li>
                    <li>CONTACT US</li>
                    <li>BUY NOW</li>
                </ul>
            </nav>
        </div>
        <div class="header">
            <img src="../assets/images/logo-default-slim.png" alt="">
            <nav>
                <ul>
                    <li>HOME</li>
                    <li>ELEMENTS</li>
                    <li>FEATURES</li>
                    <li>PAGES</li>
                    <li>PORTFOLIO</li>
                    <li>BLOG</li>
                    <li>SHOP</li>
                </ul>
            </nav>
        </div>
    </div>
</template>

<style scoped>

*{
    box-sizing: border-box;
    margin: auto;
    padding: 0;
}
.container{
    width: 1400px;
}
.header-top{
    display: flex;
    align-items: center;
    background-color: #0088CC;
}

ul{
    display: flex;
}

li{
    margin: 5px;
    list-style: none;
}

img{
    width: 100px;
}
</style>