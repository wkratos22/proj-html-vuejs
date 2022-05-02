<template>
    <div class="mt-5">
        <div class="ml-5 container text-center div-prova">
            <div class="row row-cols-2 row-cols-lg-3 g-2 g-lg-3">
                <div class="col">
                    <div class="p-3">
                        <div class="mt-4 text-left">
                            <h3><strong>ABOUT</strong></h3>
                            <p class="py-2">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac
                                consectetur
                                augue.Orci varius natoque penatibus et magnis dis parturient montes, nascetur
                                mus.</p>
                            <img class="mt-5" src="../assets/avada-movers-logo.png" alt="">
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="p-3">
                        <div class="mt-4 text-left">
                            <h3><strong>AVADA MOVERS</strong></h3>
                            <ul>
                                <li class="pt-4" v-for="element in FooterlistMover" :key="element.message">
                                    <span class="arrow">&#10095;</span>{{ element.message }}
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="p-3">
                        <div class="mt-4 text-left">
                            <h3><strong>RECENT POSTS</strong></h3>
                            <ul>
                                <li class="pt-4" v-for="element in FooterlistPosts" :key="element.message">
                                    <span class="arrow">&#10095;</span>{{ element.message }}
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="footer-bg mt-5">
            <p class="text-white text-center pt-5">&copy;Copyright 2012-2020 | Avada Theme by ThemeFusion | All Rights
                Reserved | Powered by WordPress</p>
            <div class="text-white text-center">
                <font-awesome-icon class="px-2 icon-1" icon="fa-brands fa-twitter" />
                <font-awesome-icon class="px-2 icon-2" icon="fa-brands fa-facebook" />
                <font-awesome-icon class="px-2 icon-3" icon="fa-brands fa-instagram" />
                <font-awesome-icon class="px-2 icon-4" icon="fa-brands fa-youtube" />
            </div>
            <div class="button">
                <button @click="scrollToTop" type="button" class="btn btn-primary mt-4"><strong>&#8892;</strong></button>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'FooterComp',
        methods :{
            scrollToTop() {
            window.scrollTo(0,0);
            }
        },
        data() {
            return {
                FooterlistMover: [{
                        message: 'Home',
                    },
                    {
                        message: 'Rates',
                    },
                    {
                        message: 'Testimonials',
                    },
                    {
                        message: 'Blog',
                    },
                    {
                        message: 'Free Quote',
                    },

                ],

                FooterlistPosts: [{
                        message: 'Heading Out To College?',
                    },
                    {
                        message: 'Moving Your Business?',
                    },
                    {
                        message: 'Outstanding Quality',
                    },
                    {
                        message: 'Cost of Moving',
                    },
                    {
                        message: 'Best Moving Tips',
                    },

                ],
            }

        }
    }
</script>

<style scoped lang="scss">
    ul li {
        list-style: none;
    }

    ul li:hover {
        color: #69bf14;
        cursor: pointer;
    }

    .text-left {
        text-align: left;

    }

    .arrow {
        margin-right: 10px;
        margin-left: -30px;
    }

    .footer-bg {
        background-color: #69bf14;
    }

    .btn-primary{
        background-color: rgba(63, 63, 63, 0.808);
        border: 0px;
        border-bottom-left-radius: 0;
        border-bottom-right-radius: 0;
        width: 60px;
    }

    .button{
        margin-left: 90%;
    }

    .icon-1:hover{
    color: #00ACED;
    cursor: pointer;
  }

  .icon-2:hover{
    color: #4867AA;
    cursor: pointer;
  }

  .icon-3:hover{
    color: #CF1D75;
    cursor: pointer;
  }

  .icon-4:hover{
    color: #EB080A;
    cursor: pointer;
  }

</style>