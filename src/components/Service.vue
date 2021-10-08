<template>
    <div id="my-service-section">

        <div class="container-fluid">

            <div class="row text-center">
                <div class="col-4" id="my-bg-care">
                    <h5>Emergency Care</h5>
                    <img src="../assets/images/wave-divider.png" alt="">
                    <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque
                        laudantium, totam rem aperiam, eaque
                    </p>
                    <button>LEARN MORE</button>
                </div>

                <div class="col-4" id="my-bg-diagnostics">
                    <h5>Expert Diagnostics</h5>
                    <img src="../assets/images/wave-divider.png" alt="">
                    <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque
                        laudantium, totam rem aperiam, eaque
                    </p>
                    <button>LEARN MORE</button>
                </div>

                <div class="col-4" id="my-bg-rehabilitation">
                    <h5>Superb Rehabilitation</h5>
                    <img src="../assets/images/wave-divider.png" alt="">
                    <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque
                        laudantium, totam rem aperiam, eaque
                    </p>
                    <button>LEARN MORE</button>
                </div>
            </div>

        </div>
        
    </div>
</template>

<script>
export default {
    name:"Service",
}
</script>

<style lang="scss" scoped>
@import "../style/variables.scss";

#my-service-section{
    height: 300px;
    color:white;
}

#my-bg-care,
#my-bg-diagnostics,
#my-bg-rehabilitation{
    padding-top:30px;
    padding-bottom: 40px;
    h5{
        padding-bottom: 10px;
    }
    button{
        background-color: transparent;
        border:1px solid white;
        color:white;
        padding: 8px 30px;
    }
    img{
        padding-top: 10px;
        padding-bottom: 5px;
    }
    p{
        line-height: 35px;
    }
}

#my-bg-care{
    background-color: #3ba5bd ;
}

#my-bg-diagnostics{
    background-color: #449ebf;
}

#my-bg-rehabilitation{
    background-color: #397cbb;
}
</style>