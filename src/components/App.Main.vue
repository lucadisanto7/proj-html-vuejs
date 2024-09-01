<script>
export default {
    
}
</script>
<template>
    <div class="bg-flip"></div>
    <div class="middle">
        <img src="../imgs/middle.png" alt="">
    </div>
    <main>
        <div class="container mt-350">
            <div class="row">
                <div class="col-12">
                    <div class="content text-center">
                        <h3 class="violet-text">Our Love for animation</h3>
                        <h2 class="fs-50 purple-text">We're Storytelling <br> Experts With Creative <br> Smarts</h2>
                        <h5 class="mt-4 fw-100">our culture inspires the creative and innovative spirit found troughout <br> our Studio. We breath life into new ideas!</h5>
                    </div>    
                </div>
            </div>
            <div class="row">
                <div class="col-4">
                    <div class="content">
                        <div class="smart-container">
                            <img src="../imgs/smart.png" alt="smart">
                        </div>
                    </div>
                </div>
                <div class="col-2 float-right mt-5">
                    <div class="content">
                        <div class="card yellow-gradient" style="width: 280px;">
                            <div class="icon-container">
                                <img src="../imgs/smart1.png" class="card-img-top" alt="...">
                            </div>
                            <div class="card-body text-center">
                                <h2 class="purple-text mb-3">3D modeling</h2>
                              <p class="card-text">We constantly ask questions. It helps us shape your story and deliver the results you
                                crave. Yep, we'll drill deep to deliver above and beyond your expectations..</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-2 ml-85 mt-5">
                    <div class="content">
                        <div class="card blue-gradient" style="width: 280px;">
                            <div class="icon-container">
                                <img src="../imgs/smart2.png" class="card-img-top" alt="...">
                            </div>
                            <div class="card-body text-center">
                                <h2 class="purple-text mb-3">Collaboration</h2>
                              <p class="card-text">We constantly ask questions. It helps us shape your story and deliver the results you
                                crave. Yep, we'll drill deep to deliver above and beyond your expectations..</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-2 ml-85 mt-5">
                    <div class="content">
                        <div class="card red-gradient" style="width: 280px;">
                            <div class="icon-container">
                                <img src="../imgs/smart3.png" class="card-img-top" alt="...">
                            </div>
                            <div class="card-body text-center">
                                <h2 class="purple-text mb-3">Creativity</h2>
                              <p class="card-text">We constantly ask questions. It helps us shape your story and deliver the results you
                                crave. Yep, we'll drill deep to deliver above and beyond your expectations..</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="rocket-container">
                <img src="../imgs/smart4.png" alt="rocket" class="rocket-img">
            </div>
        </div>
        <div class="mt-350">
            <img src="../imgs/shape-top.png" alt="" class="shape-top">
            <div class="background-2">
                <div class="container">
                    <h2 class="white-text pt-150 fs-50">Anidio Quick Facts</h2>
                </div>
            </div>
        </div>
    </main>
</template>
<style lang="scss">
    .bg-flip{
        background-color: #50108f;
        background-image: url('../imgs/bottom-shape.png');
        background-repeat: no-repeat;
        position: relative;
        z-index: 0;        
        height: 150px;
    }
    .middle{
        position: absolute;
        top: 50%;
        left: 25%;
    }
    .mt-350{
        margin-top: 350px;
    }
    .fs-50{
        font-size: 60px;
    }
    .purple-text{
        color: #311862;
    }
    .violet-text{
        color: #5b47c0;
    }
    .fw-100{
        font-weight: 100;
    }
    .card{
        border-radius: 40px;
    }
    .yellow-gradient{
        background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0), rgba(250, 201, 95, 0.233)); 
    }
    .blue-gradient{
        background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0), rgba(95, 131, 250, 0.233)); 
    }
    .red-gradient{
        background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0), rgba(250, 95, 95, 0.233)); 
    }
    .card-body{
        width: 270px;
        font-size: 18px;
        margin: auto;
        padding-bottom: 40px;
    }
    .icon-container{
        display: flex;
        justify-content: center;
        align-items: center;
        margin: 30px 0px 5px 0px;
    }
    .card-img-top{
        width: 100px;
    }
    .ml-85{
        margin-left: 85px;
    }
    .smart-container{
        position: absolute;
        left: 0px;
        top: 1100px;
        z-index: -1;
    }
    .rocket-img{
        position: absolute;
        right: 0px;
    }
    .shape-top{
        position: absolute;
    }
    .background-2{
        background-image: url('../imgs/counter-bg.png');
        height: 500px;
    }
    .pt-150{
        text-align: center;
        padding-top: 100px;
    }

</style>