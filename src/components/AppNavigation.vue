<script>
export default {
    name: "AppNavigation",
};
</script>

<template>
    <section>
        <div class="container">
        <div class="row-nav">
            <nav>
                <ul>
                    <li><font-awesome-icon icon="fa-regular fa-chevron-left" /></li>
                    <li>GADGETS</li>
                    <li>PHOTOGRAPHY</li>
                    <li>LIFESTYLE</li>
                    <li>FASHION</li>
                    <li>RECIPES</li>
                    <li>TRAVEL</li>
                    <li><font-awesome-icon icon="fa-regular fa-chevron-right" /></li>
                </ul>
            </nav>
        </div>
    </div>
    </section>
</template>

<style scoped>
.container{
    box-sizing: border-box;
    margin: 50px auto;
    padding: 20px;
    width: 1400px;
    /* background-color: #0088cc; */
}

section{
    background-color: #0088cc;
}

.row-nav > nav > ul{
    display: flex;
    justify-content: space-around;
}

li{
    list-style: none;
    color: #fff;
    background-color: #212529;
    padding: 20px 45px;
}
</style>