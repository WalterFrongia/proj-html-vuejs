<template>
    <div id="my-wrapping-doctors-section">
        <div id="my-doctors-section">
            <div class="container">
                <!-- SEZIONE TITOLO E IMG -->
                <div class="row pt-5">
                    <div class="col-12 text-center">
                        <img src="../assets/images/icon-5.png" alt="">
                    </div>
                </div>
                <div class="row pt-3">
                    <div class="col-12 text-center">
                        <h1>MEET OUR DOCTORS</h1>
                    </div>
                    <div class="row d-flex justify-content-center pt-5">
                        <div class="col-3 my-line"></div>
                    </div>
                </div>
                <!-- / SEZIONE TITOLO E IMG -->
                
                <!-- DESCRIZIONE DOCTORS SECTION -->
                <div class="row d-flex justify-content-center">
                    <div class="col-8 pt-5 text-center">
                        <p>Sed ut perspiaciatis omnis iste natus error sit voluptatem accusantium
                             doloremque laudatium, totam rem apreriam, aeque ipsa quae ab illo
                             inventore veritatis et quasi architetto beatae
                        </p>
                    </div>
                </div>
                <!-- / DESCRIZIONE DOCTORS SECTION -->

                <!-- SEZIONE IMG DOCTORS -->
                <div class="my-doctros-cards">
                    <div class="row d-flex justify-content-between">

                        <div class="col-3 my-cards">
                            <img src="../assets/images/doctor-1.jpg" alt="">
                            <p>JON SNOW</p>
                            <p>Anesthesiologist</p>
                            <p>At vero eos accusmus et iusto odio 
                                dignismos ducimus qui blandiits
                                praesentium volupatum delentiti atque
                            </p>
                            <div class="row">
                                <div class="col-6 d-flex my-contacts-doctor">
                                    <img src="../assets/images/logo-facebook.png" alt="">
                                    <img src="../assets/images/logo-twitter.png" alt="">
                                    <img src="../assets/images/instagram.jpg" alt="">
                                </div>
                            </div>
                        </div>

                            <div class="col-3 my-cards">
                            <img src="../assets/images/doctor-2.jpg" alt="">
                            <p>TONY STARK</p>
                            <p>Cardiologist</p>
                            <p>At vero eos accusmus et iusto odio 
                                dignismos ducimus qui blandiits
                                praesentium volupatum delentiti atque
                            </p>
                            <div class="row">
                                <div class="col-6 d-flex my-contacts-doctor">
                                    <img src="../assets/images/logo-facebook.png" alt="">
                                    <img src="../assets/images/logo-twitter.png" alt="">
                                    <img src="../assets/images/instagram.jpg" alt="">
                                </div>
                            </div>
                        </div>

                            <div class="col-3 my-cards">
                            <img src="../assets/images/doctor-3.jpg" alt="">
                            <p>ANNA SMITH</p>
                            <p>Nurse practitioner</p>
                            <p>At vero eos accusmus et iusto odio 
                                dignismos ducimus qui blandiits
                                praesentium volupatum delentiti atque
                            </p>
                            <div class="row">
                                <div class="col-6 d-flex my-contacts-doctor">
                                    <img src="../assets/images/logo-facebook.png" alt="">
                                    <img src="../assets/images/logo-twitter.png" alt="">
                                    <img src="../assets/images/instagram.jpg" alt="">
                                </div>
                            </div>
                        </div>
                        
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:"Doctors",

}
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

#my-wrapping-doctors-section{
    background-color: $fourthyColor;

    padding-top:50px;
    padding-bottom: 100px;
}
#my-doctors-section{
    margin:auto;
    width:$primaryWidth;

    p{
        line-height: 35px;
    }
}

.my-line{
    border:1px solid #bcbcbd;
    border-radius: 10px;
}

.my-doctros-cards{
    .my-cards{
        background-color: white;
        width:300px;
        margin:0;
        padding:0;
        p{
            padding:10px
        }
        
        }
        img{
            width: 100%;
        }
}

.my-contacts-doctor{
    img{
        width: 100%;
        padding:5px;
        border-radius: 10px;
    }
}
</style>