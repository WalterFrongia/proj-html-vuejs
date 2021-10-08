<template>
    <div id="my-wrapping-facilities">
        <div id="my-facilities-section">

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
    height: 500px;
}
</style>