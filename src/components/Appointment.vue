<template>
    <div id="my-wrapping-appointment-section">
        <div id="my-appointment-section">

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
    height: 500px;
}
</style>