<script>
export default {
    name: "AppSectionnews",
};
</script>

<template>
    <section>
        <div class="container">
        <div class="row-news">
            <div class="news-image">
                <img src="../assets/images/blog-46.jpg" alt="">
                <div class="description">
                    <button>PHOTOGRAPHY</button>
                    <h3>How To Take Better Concert Pictures in 30 Seconds</h3>
                </div>
            </div>

            <div class="news-image">
                <img src="../assets/images/blog-47.jpg" alt="">
                <div class="description">
                    <button>GADGETS</button>
                    <h3>Gadgets That Make Your Smartphone Even Smarter</h3>
                </div>
            </div>

            <div class="news-image">
                <img src="../assets/images/blog-48.jpg" alt="">
                <div class="description">
                    <button>TRAVEL</button>
                    <h3>20 Top-Rated Tourist Attractions in Manhattan</h3>
                </div>
            </div>

            <div class="news-image">
                <img src="../assets/images/blog-49.jpg" alt="">
                <div class="description">
                    <button>LIFESTYLE</button>
                    <h3>The Best Way to Ride a Motorcycle</h3>
                </div>
            </div>

            <div class="news-image">
                <img src="../assets/images/blog-50.jpg" alt="">
                <div class="description">
                    <button>TRAVEL</button>
                    <h3>5 Fun Things to Do at the Beach</h3>
                </div>
            </div>

            <div class="news-image">
                <img src="../assets/images/blog-51.jpg" alt="">
                <div class="description">
                    <button>RECIPES</button>
                    <h3>Amazingly Fresh Fruit And Herb Drinks For Summer</h3>
                </div>
            </div>
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
    background-color: #f7f7f7;
}
.container{
    width: 1400px;
    /* background-color: #f7f7f7; */
    padding: 50px 0;
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

button{
    background-color: #0088cc;
    padding: 5px;
    border-radius: 5px;
    border: 1px lightgrey;
    color: #fff;
}

h3{
    margin-top: 15px;
    color: #fff;
}

.news-image{
    position: relative;
}

.description{
    position: absolute;
    bottom: 30px;
    left: 30px;
}
</style>