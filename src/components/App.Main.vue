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
</style>