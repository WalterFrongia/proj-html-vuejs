<template>
    <div id="my-wrapping-interactive-icon-section">
        <div id="my-interactive-icon-section">

            <div class="row text-center">
                <div class="col-4">
                    <img src="../assets/images/client-logos-1.png" alt="">
                </div>
                <div class="col-4">
                    <img src="../assets/images/client-logos-4.png" alt="">
                </div>
                <div class="col-4">
                    <img src="../assets/images/client-logos-3.png" alt="">
                </div>
                 <!-- <div class="col-4">
                    <img src="../assets/images/client-logos-1-200x188.png" alt="">
                </div>
                <div class="col-4">
                    <img src="../assets/images/client-logos-4-200x188.png" alt="">
                </div>
                <div class="col-4">
                    <img src="../assets/images/client-logos-3-200x188.png" alt="">
                </div> -->
            </div>
            
        </div>
    </div>
</template>

<script>
export default {
    name:"InteractiveIcon",
}
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

#my-wrapping-interactive-icon-section{
    background-image: url(../assets/images/rgb-gradient-bar-for-logo-carrasel.jpg);
}

#my-interactive-icon-section{
    margin: auto;
    width: $primaryWidth;
}
</style>