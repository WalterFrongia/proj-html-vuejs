<template>

    <!-- SEZIONE HEADER CON LOGO E NAVBAR -->
    <div id="wrapping-header-section">
        <div id="header-section">
            <div class="container">
                <!-- ROW LOGO E NAVBAR -->

                <!-- LOGO -->
                <div class="row pt-3">
                    <div class="col-6 pt-2">
                        <div class="col-4">
                            <a href="">
                                <img src="../assets/images/medical_logo_1x_light.png" alt="">
                            </a>
                        </div>
                    </div>
                <!-- / LOGO -->
                    <!-- NAVBAR -->
                    <div id ="my-nav-bar" class="col-6 d-flex justify-content-end pt-2">
                        <div class="col-8">
                            <ul>
                                <li v-for="link in navBarLinks" :key="link.name"><a href="">{{link.name}}</a></li>
                            </ul>
                        </div>
                        <div class="col-4 ms-2">
                            <button>MAKE APPOINTMENT</button>
                        </div>
                    <!-- / NAV BAR -->
                    </div>
                </div>
                <!-- / ROW LOGO E NAVBAR -->
            </div>
        </div>
        <div id="text-section">
            <div class="container-fluid">
                <div class="row">
                    <div class="col-6">
                        <h1>CARING 
                            <span>FOR LIFE</span>
                        </h1>
                    </div>
                    <div class="row pt-4 pb-4">
                        <div class="col-7">
                            <p>Kind words can be short and easy to speack, but their echose are truly endless.
                                Avada Healt focuses on you as if was our own family.
                            </p>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-4">
                            <button>LEARN MORE</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'Header',
    data(){
        return{
            //ARRAY DI OGGETTI CHE SERVE PER NAV-BAR
            navBarLinks:[
                {
                    name:"HOME"
                },
                {
                    name:"ABOUT"
                },
                {
                    name:"DEPARTMENTS"
                },
                {
                    name:"ARTICLES"
                },
            ],
        }
    }
}
</script>

<style lang="scss" scoped>

@import "../style/variables.scss";

#wrapping-header-section{
    background-image: url(../assets/images/header-image-homepage.jpg);
    background-size: cover;
    background-repeat: no-repeat;
}

#header-section{
    img{
        width:100%;
        height: 100%;
    }
}

#my-nav-bar{
    display:flex;
    align-items: baseline;

}

ul{
    display: flex;
    justify-content: flex-end;

    li{
    list-style-type: none;
    text-align: center;

    font-size: $primaryFont;
        a{
            padding:0 15px;
            text-decoration: none;
            color:white;
        }
    }
}
button{
    background-color: $primaryColor;
    color:$secondaryColor;

    border:none;
    border-radius:2px;
    padding:8px 25px;
}

//Text Section
#text-section{
    margin:auto;
    width:$primaryWidth;

    padding-top:130px;
    padding-bottom: 250px;
    h1{
        color:$secondaryColor;
        span{
            color:$primaryColor;
        }
    }
    p{
        color:$secondaryColor;
    }
}

</style>