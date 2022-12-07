<script>
export default {
  name: "AppHeader",
};
</script>

<template>
    <section>
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
    </div>
    </section>

    <section class="list">
        <div class="container">
            <div class="header">
            <img src="../assets/images/logo-default-slim.png" alt="">
            <nav>
                <ul>
                    <li><h3>HOME</h3></li>
                    <li><h3>ELEMENTS</h3></li>
                    <li><h3>FEATURES</h3></li>
                    <li><h3>PAGES</h3></li>
                    <li><h3>PORTFOLIO</h3></li>
                    <li><h3>BLOG</h3></li>
                    <li><h3>SHOP</h3></li>
                </ul>
            </nav>
        </div>
        </div>
    </section>
</template>

<style scoped>

*{
    box-sizing: border-box;
    margin: auto;
    padding: 0;
}

section{
    background-color: #0088CC;
}

.list{
    background-color: #fff;
}
.container{
    width: 1400px;
}
.header-top{
    display: flex;
    align-items: center;
    /* background-color: #0088CC; */
    padding: 20px;
    color: #fff;
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
    padding: 40px 0;
}

.header > nav{
    border-top: 1px solid lightgrey;
    padding: 25px 0;
}

.header > nav > ul > li:first-child{
    color: #0088CC;
}
</style>