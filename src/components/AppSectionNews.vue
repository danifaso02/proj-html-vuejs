<script>
export default {
    name: "AppSectionnews",
};
</script>

<template>
    <div class="container">
        <div class="row-news">
            <div class="news-image">
                <img src="../assets/images/blog-46.jpg" alt="">
                <h5>title</h5>
                <h3>how to...</h3>
            </div>

            <div class="news-image">
                <img src="../assets/images/blog-46.jpg" alt="">
                <h5>title</h5>
                <h3>how to...</h3>
            </div>

            <div class="news-image">
                <img src="../assets/images/blog-46.jpg" alt="">
                <h5>title</h5>
                <h3>how to...</h3>
            </div>

            <div class="news-image">
                <img src="../assets/images/blog-46.jpg" alt="">
                <h5>title</h5>
                <h3>how to...</h3>
            </div>

            <div class="news-image">
                <img src="../assets/images/blog-46.jpg" alt="">
                <h5>title</h5>
                <h3>how to...</h3>
            </div>

            <div class="news-image">
                <img src="../assets/images/blog-46.jpg" alt="">
                <h5>title</h5>
                <h3>how to...</h3>
            </div>
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
    background-color: #f7f7f7;
}

.row-news{
    display: flex;
    flex-wrap: wrap;
}

.news-image{
    width: calc(100% / 3);
    padding: 10px;
}

img{
    width: 100%;
}
</style>