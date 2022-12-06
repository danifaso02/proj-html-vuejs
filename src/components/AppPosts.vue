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
                        <img src="../assets/images/blog-46.jpg" alt="">
                    <div class="popular-description">
                        <span>Simple ways to have a pretty face</span>
                        <br>
                        <small>January 12, 2019</small>
                    </div> 
                </div>

                <div class="post">
                        <img src="../assets/images/blog-46.jpg" alt="">
                    <div class="popular-description">
                        <span>Simple ways to have a pretty face</span>
                        <br>
                        <small>January 12, 2019</small>
                    </div> 
                </div>

                <div class="post">
                        <img src="../assets/images/blog-46.jpg" alt="">
                    <div class="popular-description">
                        <span>Simple ways to have a pretty face</span>
                        <br>
                        <small>January 12, 2019</small>
                    </div> 
                </div>

                <div class="post">
                        <img src="../assets/images/blog-46.jpg" alt="">
                    <div class="popular-description">
                        <span>Simple ways to have a pretty face</span>
                        <br>
                        <small>January 12, 2019</small>
                    </div> 
                </div>

                <div class="post">
                        <img src="../assets/images/blog-46.jpg" alt="">
                    <div class="popular-description">
                        <span>Simple ways to have a pretty face</span>
                        <br>
                        <small>January 12, 2019</small>
                    </div> 
                </div>

               
            </div>

            <div class="row-recent">

                <h4>RECENT POST</h4>
                <div class="post">
                        <img src="../assets/images/blog-46.jpg" alt="">
                    <div class="popular-description">
                        <span>Simple ways to have a pretty face</span>
                        <br>
                        <small>January 12, 2019</small>
                    </div> 
                </div>

                <div class="post">
                        <img src="../assets/images/blog-46.jpg" alt="">
                    <div class="popular-description">
                        <span>Simple ways to have a pretty face</span>
                        <br>
                        <small>January 12, 2019</small>
                    </div> 
                </div>

                <div class="post">
                        <img src="../assets/images/blog-46.jpg" alt="">
                    <div class="popular-description">
                        <span>Simple ways to have a pretty face</span>
                        <br>
                        <small>January 12, 2019</small>
                    </div> 
                </div>

                <div class="post">
                        <img src="../assets/images/blog-46.jpg" alt="">
                    <div class="popular-description">
                        <span>Simple ways to have a pretty face</span>
                        <br>
                        <small>January 12, 2019</small>
                    </div> 
                </div>

                <div class="post">
                        <img src="../assets/images/blog-46.jpg" alt="">
                    <div class="popular-description">
                        <span>Simple ways to have a pretty face</span>
                        <br>
                        <small>January 12, 2019</small>
                    </div> 
                </div>
            </div>

            <div class="row-featured">

                <h4>FEATURED POST</h4>
                <div class="featured-post">
                    <img src="../assets/images/blog-46.jpg" alt="">
                    <h5>title</h5>
                </div>

                <h4>FEATURED AUTHOR</h4>
                <div class="featured-author">
                    <div class="author-image">
                        <img src="../assets/images/blog-46.jpg" alt="">
                    </div>
                    <div class="description-author">
                        <h4>John Doe</h4>
                        <small>Lorem ipsum dolor sit amet consectetur adipisicing elit. Officia iste odit nulla, incidunt perspiciatis culpa minus fugit ad? Dignissimos magnam vel laborum earum accusantium explicabo amet repellendus harum vero beatae!</small>
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
    margin-bottom: 20px;
}

.post > img{
    width: 45px;
    height: 45px;
}

.featured-post > img{
    width: 100%;
    height: 200px;
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
    width: 70%;
}

</style>