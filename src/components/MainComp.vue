<template>
    <div>
        <div class="text-center margin-top">
            <h6>WE ARE A PROFESSIONAL</h6>
            <h1 class="solution">Full-Service Solution</h1>
        </div>

        <div class="calc text-center div-prova pt-5">
            <div class="row row-cols-2 row-cols-lg-3 g-2 g-lg-3">
                <div class="col">
                    <div class="p-3 bg-light div-photo">
                        <img src="../assets/avada-movers-serviceonephoto-final-400x255.jpg" alt="">
                        <div class="service-bg mt-4">
                            <h3><strong>Two Man Teams</strong></h3>
                            <p class="py-2">Lorem ipsum dolor sit amet, consectetur <br> adipiscing elit. Nullam ac consectetur
                                augue.<br>Orci varius natoque penatibus et magnis dis<br>parturient montes, nascetur
                                mus.</p>
                            <button type="button" class="btn btn-primary"><strong>READ MORE</strong></button>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="p-3  bg-light div-photo">
                        <img src="../assets/avada-movers-servicetwophoto-final-400x255.jpg" alt="">
                        <div class="service-bg mt-4">
                            <h3><strong>We Do All The Lifting</strong></h3>
                            <p class="py-2">Lorem ipsum dolor sit amet, consectetur <br> adipiscing elit. Nullam ac consectetur
                                augue.<br>Orci varius natoque penatibus et magnis dis<br>parturient montes, nascetur
                                mus.</p>
                            <button type="button" class="btn btn-primary"><strong>READ MORE</strong></button>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="p-3 bg-light div-photo">
                        <img src="../assets/avada-movers-servicethreephoto-final-400x255.jpg" alt="">
                        <div class="service-bg mt-4">
                            <h3><strong>Coast To Coast</strong></h3>
                            <p class="py-2">Lorem ipsum dolor sit amet, consectetur <br> adipiscing elit. Nullam ac consectetur
                                augue.<br>Orci varius natoque penatibus et magnis dis<br>parturient montes, nascetur
                                mus.</p>
                            <button type="button" class="btn btn-primary"><strong>READ MORE</strong></button>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div class="bg-image mt-5">
            <div class="col text-center flex">
                    <div class="p-3 bg-lime div-green position">
                        <div class="bg-green p-5">
                            <h6 class="text-white"><strong>WE REMOVE THE HEADACHE FROM MOVING</strong></h6>
                            <h1 class="text-white">Move With Ease</h1>
                            <hr class="hr text-white">
                            <p class="text-white">With our super simple service we can take you from getting a quote, right throught to being in your ne home with all of your belongings securley packed and safely delivered, even in the rooms of your choice.</p>
                            <button type="button" class="btn btn-primary"><strong>GET A FREE QUOTE NOW</strong></button>
                        </div>
                    </div>
                </div>
        </div>

    </div>
</template>

<script>
    export default {
        name: 'MainComp',

    }
</script>

<style scoped lang="scss">
    *{
        --button-color: #1b74c3;
        --button-color-hover: #2d86cf;
    }


    h1 {
        font-size: 50px;
        font-weight: 700;
    }

    h6 {
        color: gray;
        font-weight: 700;
        font-size: 15px;
    }

    .margin-top{
        margin-top: 130px;
    }

    .solution {
        color: #69bf14;
    }

    .div-prova {
        height: 700px;
    }

    .div-photo {
        width: 430px;
    }

    .calc {
        width: calc(100%/1 - 500px);
        margin-left: 14%;
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

    .service-bg{
        background-color: #fefefe;
        padding-top: 2rem;
        padding-bottom: 2rem;
    }

    h3{
        color: #1975c0;
    }

    .bg-image {
        background-image: url(../assets/avada-movers-movewithease-background-new.jpg);
        background-repeat: no-repeat ;
        background-size: cover;
        max-width: 100%;
        height: 750px;
    }

    .div-green{
        width: 600px;
    }

    .hr{
        width: 400px;
        margin-left: 14%;
    }

    .bg-lime{
        background-color: #69bf14;
    }

    .bg-green{
        background-color: #8fce53;
    }

    .flex{
        display: flex;
        justify-content: center;
    }

    .position{
        margin-top: 9%;
        margin-left: 35%;
    }
</style>