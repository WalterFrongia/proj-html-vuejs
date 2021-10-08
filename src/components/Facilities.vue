<template>
    <div id="my-wrapping-facilities">
        <div id="my-facilities-section">

            <!-- ICONA TITOLO E DESCRIZIONE FACILITIES SECTION -->
            <div class="row pt-2">
                <div class="col-12 text-center">
                    <img src="../assets/images/icon-7.png" alt="">
                </div>
            </div>
        
            <div class="row pt-3">
                <div class="col-12 text-center">
                    <h1>TOUR OUR FACILITIES</h1>
                </div>
            </div>
            <div class="row d-flex justify-content-center pt-3">
                <div class="col-3 my-line"></div>
            </div>
            <div class="row d-flex justify-content-center">
                <div class="col-8 pt-3 text-center">
                    <p>Sed ut perspiaciatis omnis iste natus error sit voluptatem accusantium
                        doloremque laudatium, totam rem apreriam, aeque ipsa quae ab illo
                        inventore veritatis et quasi architetto beatae
                    </p>
                </div>
            </div>
            <div class="row pt-4 d-flex justify-content-center">
                <div class="col-12 text-center">
                    <img src="../assets/images/play-icon.png" alt="">
                </div>
            </div>
            <!-- / ICONA TITOLO E DESCRIZIONE FACILITIES SECTION -->

        </div>
    </div>
</template>

<script>
export default {
    name:"Facilities",
}
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

#my-wrapping-facilities{
    background-image: url(../assets/images/paralax-bg-tour-facilities.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    
    padding-top: 50px;
}
#my-facilities-section{
    margin:auto;
    width:$primaryWidth;

    padding-bottom: 100px;

    h1{
        color: white;
    }
    p{
        color:white;
        line-height: 35px;
    }
}
</style>