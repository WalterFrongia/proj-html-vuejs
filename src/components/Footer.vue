<template>
    <div id="footer-section">
        <div class="container">

            <div class="row">
                <!-- INFORMAZIONI AVADA HEALT FOOTER -->
                <div class="col-4">
                    <div class="row">
                        <div class="col-7 pb-3">
                            <img src="../assets/images/medical_logo_1x_dark.png" alt="">
                        </div>
                    
                        <div class="col-12">
                            <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque
                                audantium, totam rem aperiam, eaque ipsa quae ab illo inventore vritatis et quasi
                                architecto beatae
                            </p>
                        </div>
                        <div class="col-12 pt-2">
                            <div class="my-line"></div>
                        </div>
                        <div class="col-12">
                            <h5>LEARN MORE ABOUT US</h5>
                        </div>
                        <div clas="row">
                            <div class="col-5 d-flex pt-3">
                                <img src="../assets/images/logo-facebook.png" alt="">
                                <img src="../assets/images/logo-twitter.png" alt="">
                                <img src="../assets/images/instagram.jpg" alt="">
                                <img src="../assets/images/logo-youtube.png" alt="">
                            </div>
                        </div>
                    </div>
                </div>
                <!-- /INFORMAZIONI AVADA HEALT FOOTER -->
                
                <!-- CONTACT INFORMATION FOOTER -->
                <div class="col-4 ps-3">                    
                    <div class="row">
                        <div class="col-12 pb-3">
                            <h5>CONTACT INFORMATION</h5>
                        </div>
                        <div class="row">
                            <div class="col-2 my-blu-line">
                            </div>
                        </div>
                        <div class="row pt-3">
                            <div class="col-12 d-flex">
                                <i class="fas fa-map-marker-alt"></i>
                                <p>121 King Street, London Uniter Kingdom</p>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-12 d-flex">
                                <i class="fas fa-phone"></i>
                                <p>1.800.458.556</p>
                            </div>
                        </div>
                    </div>
                </div>
                <!-- / CONTACT INFORMATION FOOTER -->

                <!-- MEDICAL DEPARTMENTS FOOTER -->
                <div class="col-4">
                    <div class="row">
                        <div class="col-12 pb-3">
                            <h5>MEDICAL DEPARTMENTS</h5>
                        </div>
                        <div class="row">
                            <div class="col-2 my-blu-line">
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-12">
                                <ul>
                                    <li v-for="link in medicaDepartments" :key="link.name"><a href="">{{link.name}}</a></li>
                                </ul>
                            </div>
                        </div>
                    </div>

                </div>
                <!-- /MEDICAL DEPARTMENTS FOOTER -->
            </div>

        </div>
    </div>
</template>

<script>
export default {
    name:'Footer',
    data(){
        return{
            //ARRAY DI OGGETTI CHE SERVE PER LINK FOOTER
            medicaDepartments:[
                {
                    name:"Cardiology"
                },
                {
                    name:"Prediatrics"
                },
                {
                    name:"Diabetes Care"
                },
                {
                    name:"Pre-natel Care"
                },
                {
                    name:"Ultrasound Echicardiogram"
                },
            ],
        }
    }
}
</script>

<style lang="scss" scoped>

@import "../style/variables.scss";

#footer-section{
    padding-top:50px;

    height: 500px;

    p{
        line-height: 35px;
    }

    img{
        width:100%;

        border-radius: 10px;
        margin:0 5px;
    }

    i{
        font-size: 1.2rem;
        color:$primaryColor;
        vertical-align: baseline;
        padding-right: 10px;
    }
}

.my-line{
    border:1px solid #bcbcbd;
    border-radius: 10px;
}

.my-blu-line{
    border:1px solid $primaryColor;
    border-radius: 10px;
}
</style>