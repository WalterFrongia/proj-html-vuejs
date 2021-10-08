<template>
    <div id="my-welcome-section">
        <div class="container">
            <!-- SEZIONE TITOLO E TESTO -->
            <div class="row">
                <div class="col-12 text-center pt-5">
                   <h1>Welcome to Avada Health</h1>
                </div>
            </div>
            <div class="row text-center d-flex justify-content-center">
                <div class="col-7 pt-3">
                    <p>Sed ut perspiaciatis omnis iste natus error sit voluptatem accusantium
                        doloremque laudatium, totam rem apreriam, aeque ipsa quae ab illo
                    </p>
                </div>
            </div>
            <!-- / TITOLO E TESTO -->

            <!-- SEZIONE CARTE -->
            <div class="my-welcome-cards">
               <div class="row">
                   <div class="col-3 text-center">
                       <img src="../assets/images/icon-1.png" alt="">
                       <p>Sed ut perspiaciatis omnis iste natus error sit voluptatem accusantium</p>
                   </div>
                    <div class="col-3 text-center">
                       <img src="../assets/images/icon-2.png" alt="">
                       <p>Sed ut perspiaciatis omnis iste natus error sit voluptatem accusantium</p>
                   </div>
                    <div class="col-3 text-center">
                       <img src="../assets/images/icon-3.png" alt="">
                       <p>Sed ut perspiaciatis omnis iste natus error sit voluptatem accusantium</p>
                   </div>
                    <div class="col-3 text-center">
                       <img src="../assets/images/icon-4.png" alt="">
                       <p>Sed ut perspiaciatis omnis iste natus error sit voluptatem accusantium</p>
                   </div>
               </div>
            </div>
            <!-- / SEZIONE CARTE -->

        </div>
    </div>
</template>

<script>
export default {
    name:'welcome',
    components: {
    },
    data(){
    }
}
</script>

<style lang="scss" scoped>

@import "../style/variables.scss";

#my-welcome-section{
    margin:auto;
    width:$primaryWidth;
    
    h1{
        color:$thirdColor;
    }
    p{
        line-height: 35px;
    }
    img{
        cursor: pointer;
    }
}

.my-welcome-cards{
    padding-top: 50px;
    padding-bottom:100px;
}
</style>