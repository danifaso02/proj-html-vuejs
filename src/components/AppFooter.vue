<script>

export default {
    name: "AppFooter",
};
</script>

<template>
    <section class="main-footer">
        <div class="container">
            <div class="row-info">
            <div class="blog">
                <h5>ABOUT THE BLOG</h5>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Repudiandae!</p>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Repudiandae!</p>
                <small>VIEW MORE</small>
            </div>

            <div class="recent-posts">
                    <h5>RECENT POSTS</h5>
                    <div class="posts">
                        <div class="row-posts">
                        <div class="image">
                            <img src="../assets/images/blog-65.jpg" alt="">
                        </div>
                        <div class="description">
                            <span>Lorem ipsum dolor sit amet consectetur adipisicing elit.</span>
                            <br>
                            <small>12:53 AM Dec 19th</small>
                        </div>
                        </div>
                        <div class="row-posts">
                            <div class="image">
                                <img src="../assets/images/blog-65.jpg" alt="">
                            </div>
                        <div class="description">
                            <span>Lorem ipsum dolor sit amet consectetur adipisicing elit.</span>
                            <br>
                            <small>12:53 AM Dec 19th</small>
                        </div>
                        </div>
                    </div>
            </div>


            <div class="recent-comments">
                <div class="comment">
                    <h5>RECENT COMMENTS</h5>
                    <span><strong>John Doe</strong> commented on <span>lorem ipsum dolor sit amet.</span></span>
                    <br>
                    <small>12:55 AM Dec 19th</small>
                </div>
                <div class="comment">
                    <span><strong>John Doe</strong> commented on <span>lorem ipsum dolor sit amet.</span></span>
                    <br>
                    <small>12:55 AM Dec 19th</small>
                </div>
            </div>

            <div class="categories">
                <h5>CATEGORIES</h5>
                <div class="row-list">
                    <ul>
                        <li>GADGETS</li>
                        <li>PHOTOGRAPHY</li>
                        <li>LIFESTYLE</li>
                        <li>FASHION</li>
                        <li>RECIPES</li>
                        <li>TRAVEL</li>
                        <li>BUSINESS</li>
                        <li>ARCHITECTURE</li>
                        <li>REVIEWS</li>
                        <li>SPORTS</li>
                        <li>VIDEOS</li>
                        <li>TECHNOLOGY</li>
                        <li>DESIGN</li>
                    </ul>
                </div>
            </div>
          </div>
        </div>
    </section>

        <section class="under-footer">
            <div class="container">
                <div class="row-under-footer">
                <div class="logo">
                    <img src="../assets/images/logo-footer.png" alt="">
                    <small>@Copyright 2020. All Rights Deserved</small>
                </div>
                <div class="contact-us">
                    <ul>
                        <li>FAQ's</li>
                        <li>Sitemap</li>
                        <li>Contact us</li>
                    </ul>
                </div>
                </div>
            </div>
            <div class="btn">
                <button><font-awesome-icon icon="fa-regular fa-chevron-right" /></button>
            </div>
        </section>
</template>

<style scoped>
.container{
    box-sizing: border-box;
    margin: auto;
    padding: 0;
    width: 1400px;
}

.main-footer{
    background-color: #212529;
}

.under-footer{
   background-color: #1c2023; 
}

img{
    width: 100%;
}
.row-info{
    display: flex;
}

h5{
    color: #fff;
}

.blog > small{
    color: #fff;
}

strong{
    color: #fff;
}

.blog, .recent-posts, .recent-comments, .categories{
    width: calc(100% / 4);
}
.row-posts{
    display: flex;
    margin-bottom: 20px;
}


.blog > p{
    color: grey;
    font-size: 12px;
}
.image{
    width: 50px;
}

.image > img{
    border-radius: 100%;
}

.description{
    width: 50%;
    font-size: 12px;
    padding-left: 10px;
}

.description > span{
    color: #c5c6c7;
}

.description > small{
    color: grey;
}

.comment{
    margin-bottom: 20px;
    font-size: 12px;
    color: grey;
}

.comment > span > span{
    color: #0088cc;
}
.row-list > ul > li{
    background-color: #000000;
    color: #fff;
    padding: 7px;
    margin: 0 7px 20px 0;
    list-style: none;
    font-size: 10px;
    border-radius: 10px;
}
.row-list > ul{
    display: flex;
    flex-wrap: wrap;
    padding: 0;
}

.row-under-footer{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 30px 0;
    color: grey;
}

.logo{
    display: flex;
    align-items: center;
}

.logo > img{
    width: 100px;
    margin-right: 40px;
}

.contact-us > ul{
    display: flex;
}

.contact-us > ul > li{
    list-style: none;
    margin: 0 10px;
    /* color: grey; */
}

.btn{
    display: flex;
    justify-content: flex-end;
    padding: 20px;
}
</style>