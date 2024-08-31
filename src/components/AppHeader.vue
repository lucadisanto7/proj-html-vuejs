<template>
    <header class="bg">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div class="content mt-4">
                        <img class="logo" src="../imgs/logo.png" alt="logo">
                        <div class="planets">
                            <img src="../imgs/globe1.png" alt="Planet 1" class="planet-image planet-1">
                            <img src="../imgs/globe2.png" alt="Planet 2" class="planet-image planet-2">
                            <img src="../imgs/globe3.png" alt="Planet 3" class="planet-image planet-3">
                            <img src="../imgs/dots-right.png" alt="Dots right" class="planet-image dots-right">
                            <img src="../imgs/dots-left.png" alt="Dots left" class="planet-image dots-left">
                        </div>
                        <ul class="list">
                            <li> <a class="list-itm white-text" href="">Home</a></li>
                            <li> <a class="list-itm white-text" href="">About Us</a></li>
                            <li> <a class="list-itm white-text" href="">Portfolio</a></li>
                            <li> <a class="list-itm white-text" href="">Our Process</a></li>
                            <li> <a class="list-itm white-text" href="">Pricing</a></li>
                            <li> <a class="list-itm white-text" href="">Blog</a></li>
                            <li> <a class="list-itm white-text" href="">Contact</a></li>
                            <li> <a class="list-itm black-text" href=""><span class="label">Get a Quote</span></a></li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-12">
                    <div class="content">
                        <div class="orange-text text-center mt-80 fs-4">
                            Imagine, Create, Experience
                        </div>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-2">
                    <img src="../imgs/left-man.png" alt="Left Character" class="character-image mr-20">
                </div>
                <div class="col-9">
                    <div class="content mt-3 white-text text-center">
                        <h1 class="fs-80">We Animate <br> With Ninja-Like Precision</h1>
                        <h5 class="mt-4 fs-23">We are a character-driven animation studio striving to make high-quality animations</h5>
                        <div class="content label-container">
                            <a href="" class="list-itm black-text"><span class="label">Start a Project</span></a>
                            <a href="" class="list-itm white-text"><span class="label-dark">Portfolio</span></a>
                        </div>
                    </div>
                </div>
                <div class="col-1">
                    <img src="../imgs/right-man.png" alt="Right Character" class="character-image">
                </div>
            </div>
        </div>
    </header>
</template>

<style lang="scss">
.bg {
    background-color: #311862;
    background-image: url('../imgs/banner-bg.png');
    background-repeat: no-repeat;
    position: relative;
    z-index: 0;
}

.bg-flip{
    background-image: url('../imgs/banner-bg.png');
    height: 100px;
}

.white-text {
    color: white;
}

.orange-text {
    color: #FF7A1F;
}

.mt-80 {
    margin-top: 80px;
    margin-left: 100px;
}

.black-text {
    color: black;
}

.list {
    list-style-type: none;
    display: flex;
    gap: 30px;
    float: right;
    position: relative;
    z-index: 3;
}

.list-itm {
    text-decoration: none;
    z-index: 3;
}

.fs-23{
    font-size: 23px;
}

.fs-80 {
    font-size: 80px;
}

.logo {
    position: absolute;
    top: 15px;
    z-index: 4;
}

.label-container{
    display: flex;
    gap: 20px;
    justify-content: center;
    margin-top: 70px;
}

.label {
    background-color: #FFDFED;
    padding: 15px 35px;
    border-radius: 500px;
    box-shadow: 0 0 8px #FFDFED;
    z-index: 3;
    font-size: 18px;
}

.label-dark{
    background-color: #311862;
    border: 1px solid #FFDFED;
    padding: 15px 35px;
    border-radius: 500px;
    box-shadow: 0 0 8px #FFDFED;
    z-index: 3;
    font-size: 18px;
    
}

.character-image {
    width: 230px;
    height: auto;
    margin-top: 70px;
    position: relative;
    z-index: 3;
}

.planets {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: -1;
}

.planet-image {
    position: absolute;
    width: 100px;
    height: auto;
    z-index: -1;
}

.planet-1 {
    top: 90px;
    left: 400px;
    width: 130px;
}

.planet-2{
    top: 175px;
    right: 30%;
    width: 100px;
}

.planet-3 {
    top: -200px;
    right: 40%;
    width: 300px;
    z-index: -1;
}

.dots-right{
    top: 50px;
    right: 3%;
    width: 800px;
    z-index: -1;
}

.dots-left{
    top: 50px;
    left: 3%;
    width: 800px;
    z-index: -1;
}
</style>
