<template>
    <div id="welcome-section">
        <div class="container">
            <div class="row">
                <div class="col-12 text-center pt-5">
                   <h1>Welcome to Avada Health</h1>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'welcome',
}
</script>

<style lang="scss" scoped>

@import "../style/variables.scss";

#welcome-section{
    margin:auto;
    width:$primaryWidth;
    height: 500px; //atezza impostata per capire grandezze pagina, poi verrà rimossa
    h1{
        color:$thirdColor;
    }
}

</style>