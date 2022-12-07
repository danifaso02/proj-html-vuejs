<script>
export default {
    name: "AppPosts",
};
</script>

<template>
    <div class="container">
        <div class="row-posts">
            <div class="row-popular">

                <h4>POPULAR POST</h4>
                <div class="post">
                        <img src="../assets/images/blog-55.jpg" alt="">
                    <div class="popular-description">
                        <span>Simple Ways to Have a Pretty Face</span>
                        <br>
                        <small>January 12, 2019</small>
                    </div> 
                </div>

                <div class="post">
                        <img src="../assets/images/blog-56.jpg" alt="">
                    <div class="popular-description">
                        <span>Ranking the greatest players in basketball</span>
                        <br>
                        <small>January 12, 2019</small>
                    </div> 
                </div>

                <div class="post">
                        <img src="../assets/images/blog-57.jpg" alt="">
                    <div class="popular-description">
                        <span>4 Ways to Look Cool in Glasses</span>
                        <br>
                        <small>January 12, 2019</small>
                    </div> 
                </div>

                <div class="post">
                        <img src="../assets/images/blog-58.jpg" alt="">
                    <div class="popular-description">
                        <span>Top Camper Trailer Towing Tips</span>
                        <br>
                        <small>January 12, 2019</small>
                    </div> 
                </div>

                <div class="post">
                        <img src="../assets/images/blog-59.jpg" alt="">
                    <div class="popular-description">
                        <span>5 Lovely Walks in New York</span>
                        <br>
                        <small>January 12, 2019</small>
                    </div> 
                </div>

               
            </div>

            <div class="row-recent">

                <h4>RECENT POST</h4>
                <div class="post">
                        <img src="../assets/images/blog-65.jpg" alt="">
                    <div class="popular-description">
                        <span>Main Reasons To Stop Texting And Driving</span>
                        <br>
                        <small>January 12, 2019</small>
                    </div> 
                </div>

                <div class="post">
                        <img src="../assets/images/blog-66 (1).jpg" alt="">
                    <div class="popular-description">
                        <span>Tips to Help You Quickly Prepare your Lunch</span>
                        <br>
                        <small>January 12, 2019</small>
                    </div> 
                </div>

                <div class="post">
                        <img src="../assets/images/blog-67.jpg" alt="">
                    <div class="popular-description">
                        <span>Why should I buy a smartwatch?</span>
                        <br>
                        <small>January 12, 2019</small>
                    </div> 
                </div>

                <div class="post">
                        <img src="../assets/images/blog-68.jpg" alt="">
                    <div class="popular-description">
                        <span>The best augmented reality smartglasses</span>
                        <br>
                        <small>January 12, 2019</small>
                    </div> 
                </div>

                <div class="post">
                        <img src="../assets/images/blog-69.jpg" alt="">
                    <div class="popular-description">
                        <span>12 Healthiest Foods to Eat for Breakfast</span>
                        <br>
                        <small>January 12, 2019</small>
                    </div> 
                </div>
            </div>

            <div class="row-featured">

                <h4>FEATURED POST</h4>
                <div class="featured-post">
                    <img src="../assets/images/blog-66.jpg" alt="">
                    <div class="featured-description">
                        <span>RECIPES</span>
                        <h3>Tips to Help You Quickly Prepare your Lunch</h3>
                    </div>
                </div>

                <h4>FEATURED AUTHOR</h4>
                <div class="featured-author">
                    <div class="author-image">
                        <img src="../assets/images/avatar.jpg" alt="">
                    </div>
                    <div class="description-author">
                        <h4>John Doe</h4>
                        <small>Lorem ipsum dolor sit amet consectetur adipisicing elit. Officia iste odit nulla, incidunt perspiciatis culpa minus fugit ad?</small>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>

.container{
    box-sizing: border-box;
    margin: auto;
    padding: 0;
    width: 1400px;
}

.row-posts{
    display: flex;
}

.row-popular{
    width: calc(100% / 3);
}

.row-recent{
    width: calc(100% / 3);
}

.row-featured{
    width: calc(100% / 3);
}

.post{
    display: flex;
    align-items: center;
    margin-bottom: 30px;
}

.post > img{
    width: 45px;
    height: 45px;
}

.featured-post{
    position: relative;
    color: #fff;
}

.featured-description{
    position: absolute;
    bottom: 20px;
    left: 20px;
}

.featured-description > span{
    background-color: #0088cc;
    padding: 5px;
    border-radius: 5px;
}
.featured-post > img{
    width: 100%;
}

.popular-description{
    margin-left: 10px;
}

.featured-author{
    display: flex;
    align-items: center;
}

.author-image{
    width: 30%;
}

.author-image > img{
    width: 100%;
}
.description-author{
    padding-left: 20px;
    width: 70%;
}

.description-author > h4{
    margin: 5px 0;
}

</style>