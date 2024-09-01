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
                        <h3>Our Love for animation</h3>
                        <h2 class="fs-50">We're Storytelling <br> Experts With Creative <br> Smarts</h2>
                        <h5 class="mt-4">our culture inspires the creative and innovative spirit found troughout <br> our Studio. We breath life into new ideas!</h5>
                    </div>    
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
</style>