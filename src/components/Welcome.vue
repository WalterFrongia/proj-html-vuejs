<template>
    <div id="my-welcome-section">
        <div class="container">
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

#my-welcome-section{
    margin:auto;
    width:$primaryWidth;

    height: 500px; //atezza impostata per capire grandezze pagina, poi verrà rimossa
    h1{
        color:$thirdColor;
    }
}

</style>