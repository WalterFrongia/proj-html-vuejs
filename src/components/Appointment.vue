<template>
    <div id="my-wrapping-appointment-section">
        <div id="my-appointment-section">

            <!-- TITOLO E TESTO SEZIONE APPUNTAMENTI -->
            <div class="row d-flex justify-content-center">
                <div class="col-8 text-center">
                    <h1>Make An Appointment</h1>
                </div>
            </div>
            <div class="row d-flex justify-content-center pt-3 pb-4">
                <div class="col-3 my-line"></div>
            </div>
            <div class="row d-flex justify-content-center">
                <div class="col-7 text-center">
                    <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque
                        laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore vritatis et quasi
                        architecto beatae
                    </p>
                </div>
            </div>
            <!-- / TITOLO E TESTO SEZIONE APPUNTAMENTI -->

            <!-- INPUT TEXT PER INSERIRE NOME ED EMAIL -->
            <div class="row d-flex justify-content-center pb-4">
                <div class="col-4">
                    <input type="text" placeholder="Name*">
                </div>

                <div class="col-4">
                    <input type="text" placeholder="Email*">
                </div>
            </div>
            <!-- / INPUT TEXT PER INSERIRE NOME ED EMAIL -->

            <!-- INPUT TEXT PER INSEIRE NUMERO E DATA APPUNTAMENTO -->
            <div class="row d-flex justify-content-center">
                <div class="col-4">
                    <input type="text" placeholder="Phone Number">
                </div>
                <div class="col-4 pb-4">
                    <input type="text" placeholder="Appointment Date">
                </div>
            </div>
            <!-- / INPUT TEXT PER INSEIRE NUMERO E DATA APPUNTAMENTO -->

            <!-- INPUT PER INSERIRE INFO  -->
            <div class="row d-flex justify-content-center">
                <div class="col-8">
                    <input class="pb-5" type="text" placeholder="How can we help?*">
                </div>
            </div>
            <!-- / INPUT PER INSERIRE INFO  -->

            <!-- BUTTON  -->
            <div class="row d-flex justify-content-center pt-3">
                <div class="col-8">
                    <button>MAKE AN APPOINTMENT</button>
                </div>
            </div>
            <!-- / BUTTON  -->
            
        </div>
    </div>
</template>

<script>
export default {
    name:"Appointment",
}
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

#my-wrapping-appointment-section{
    background-image: url(../assets/images/make-an-appointment.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
}

#my-appointment-section{
    margin:auto;
    width:$primaryWidth;

    color:white;
    padding-top:100px;
    padding-bottom:100px;

    p{
        line-height: 35px;
    }
    input{
        background-color: transparent;
        color:white;
        border:1px solid white;
        padding:10px 10px;
        width: 100%;
    }
    button{
    background-color: $primaryColor;
    color:$secondaryColor;

    border:none;
    border-radius:2px;
    padding:10px 0;
    width:100%;
}
}

.my-line{
    border:1px solid #bcbcbd;
    border-radius: 10px;
}
</style>