<template>
    <div class="bg-image">
        <div class="bg-green p-5 text-center">
            <div class="mt-5">
                <h6 class="subtitle">HAPPY CUSTOMERS</h6>
                <h1 class="title">Testimonials</h1>
            </div>
        </div>

        <div class="calc text-center div-prova">
            <div class="row row-cols-2 row-cols-lg-3 g-2 g-lg-3">
                <div class="col">
                    <div class="p-3">
                        <img class="rounded-circle" src="../assets/avada-movers-johndoe-final-200x200.jpg" alt="">
                        <div class="service-bg mt-4">
                            <h3><strong>John Doe</strong></h3>
                            <p class="py-2">"Lorem ipsum dolor sit amet, consectetur <br> adipiscing elit. Nullam ac consectetur
                                augue.<br>Orci varius natoque penatibus et magnis dis<br>parturient montes, nascetur
                                mus."</p>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="p-3">
                        <img class="rounded-circle" src="../assets/avada-movers-janedoe-final-200x200.jpg" alt="">
                        <div class="service-bg mt-4">
                            <h3><strong>Jane Doe</strong></h3>
                            <p class="py-2">"Lorem ipsum dolor sit amet, consectetur <br> adipiscing elit. Nullam ac consectetur
                                augue.<br>Orci varius natoque penatibus et magnis dis<br>parturient montes, nascetur
                                mus."</p>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="p-3">
                        <img class="rounded-circle" src="../assets/avada-movers-johnsmith-final-200x200.jpg" alt="">
                        <div class="service-bg mt-4">
                            <h3><strong>John Smith</strong></h3>
                            <p class="py-2">"Lorem ipsum dolor sit amet, consectetur <br> adipiscing elit. Nullam ac consectetur
                                augue.<br>Orci varius natoque penatibus et magnis dis<br>parturient montes, nascetur
                                mus."</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div class="text-center mt-3 py-5">
            <button type="button" class="btn btn-primary"><strong>READ MORE TESTIMONIALS</strong></button>
        </div>

        <div class="bg-quote text-center">
            <div class="mt-5">
                <div class="margin">
                    <h1 class="title">Request A Free Quote</h1>
                    <p>Lorem ipsum dolor sit amet, consecteur adipiscing elit. Nullam ac consectetur augue. Orci varius natoque <br> penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>
                    <button type="button" class="btn btn-primary mt-4"><strong>CLICK HERE</strong></button>
                </div>
            </div>
        </div>

        <div class="barra-verde">
        </div>
    </div>
</template>

<script>
    export default {
        //Cambiare il nome con quello del componente creato
        name: 'HeaderComp',
    }
</script>

<style scoped lang="scss">
    *{
        --button-color: #1b74c3;
        --button-color-hover: #2d86cf;
    }
    //TESTIMONIALS
    .bg-image {
        background-image: url(../assets/avada-movers-testimonial-background.jpg);
        background-repeat: no-repeat ;
        background-size: cover;
    }

    .title{
        color: #69bf14;
        font-weight: 900;
    }

    .subtitle{
        color: grey;
        font-weight: 900;
    }

    .btn-primary {
        background-color: var(--button-color) ;
        border-radius: 40px;
        padding-left: 20px;
        padding-right: 20px;
        font-size: 15px;
    }

    .btn-primary:hover {
        background-color: var(--button-color-hover);
        border: 1px solid var(--button-color-hover) ;
    }
    //FREE QUOTE
    .bg-quote{
        background-image: url(../assets/avada-movers-request-quote-background.jpg);
        background-repeat: no-repeat ;
        background-size: cover;
        height: 500px;
    }

    .margin{
        padding-top: 150px;
    }

    .barra-verde{
        background-color: #69bf14;
        height: 20px;
    }

</style>