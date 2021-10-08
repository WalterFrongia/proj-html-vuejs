<template>
    <div id="my-wrapping-appointment-section">
        <div id="my-appointment-section">
            <div class="row d-flex justify-content-center">
                <div class="col-6">
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

    height: 500px;
    color:white;
    padding-top:100px;
}

.my-line{
    border:1px solid #bcbcbd;
    border-radius: 10px;
}
</style>