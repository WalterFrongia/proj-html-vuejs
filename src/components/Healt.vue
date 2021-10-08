<template>
    <div id="healt-section">
        <!-- SEZIONE ICONA TITOLO E DESCRIZIONE HEALT SECTION -->
        <div class="row pt-5">
            <div class="col-12 text-center">
                <img src="../assets/images/icon-6.png" alt="">
            </div>
        </div>
        <div class="row pt-3">
            <div class="col-12 text-center">
                <h1>OUR HEALT SERVICES</h1>
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
        <!-- / SEZIONE ICONA TITOLO E DESCRIZIONE HEALT SECTION -->

        <div class="my-healt-cards">
               <div class="row">
                   <div class="col-4 text-center">
                       <img src="../assets/images/icon-14.png" alt="">
                       <p>At vero eos accusmus et iusto odio 
                            dignismos ducimus qui blandiits
                            praesentium volupatum delentiti atque
                        </p>
                   </div>
                    <div class="col-4 text-center">
                       <img src="../assets/images/icon-15.png" alt="">
                       <p>At vero eos accusmus et iusto odio 
                            dignismos ducimus qui blandiits
                            praesentium volupatum delentiti atque
                        </p>
                   </div>
                    <div class="col-4 text-center">
                       <img src="../assets/images/icon-16.png" alt="">
                       <p>At vero eos accusmus et iusto odio 
                            dignismos ducimus qui blandiits
                            praesentium volupatum delentiti atque
                        </p>
                   </div>
               </div>

               <div class="row">
                   <div class="col-4 text-center">
                       <img src="../assets/images/icon-11.png" alt="">
                       <p>At vero eos accusmus et iusto odio 
                            dignismos ducimus qui blandiits
                            praesentium volupatum delentiti atque
                        </p>
                   </div>
                    <div class="col-4 text-center">
                       <img src="../assets/images/icon-12.png" alt="">
                       <p>At vero eos accusmus et iusto odio 
                            dignismos ducimus qui blandiits
                            praesentium volupatum delentiti atque
                        </p>
                   </div>
                    <div class="col-4 text-center">
                       <img src="../assets/images/icon-13.png" alt="">
                       <p>At vero eos accusmus et iusto odio 
                            dignismos ducimus qui blandiits
                            praesentium volupatum delentiti atque
                        </p>
                   </div>
               </div>
            </div>
    </div>
            
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

#healt-section{
    margin:auto;
    width:$primaryWidth;
    height: 500px;
    p{
        line-height: 35px;
    }
}

.my-line{
    border:1px solid #bcbcbd;
    border-radius: 10px;
}

.my-healt-cards{
    padding-top: 50px;
    padding-bottom:100px;
}
</style>