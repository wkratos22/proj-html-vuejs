<template>
    <div>
        <div class="bg-image">
            <div class="container space mt-4">
                <img class="image" src="../assets/avada-movers-logo.png" alt="">
                <ul class="inline">
                    <li class="px-4 align" v-for="element in NavBar" :key="element.message">
                        {{ element.message }}
                    </li>
                    <li class="quote p-2 px-4">
                        FREE QUOTE
                    </li>
                </ul>
            </div>
            <div class="head-text">
                <h6><strong>MOVING WITHOUT THE HASSLE</strong></h6>
                <h1><strong>WE MAKE IT SIMPLE</strong></h1>
                <h6><strong>PROFESSIONAL SERVICE WITH QUALITY AND CUSTOMER SATISFACTION</strong></h6>
            </div>
        </div>
        <div class="bg-blue text-center">
            <div class="p-5">
                <font-awesome-icon class="text-white px-2" icon="fa-solid fa-paper-plane" />
                <p class="text-white inline">GET A FREE QUOTE ONLINE NOW!</p>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'headerComp1',
        data() {
            return {
                NavBar: [{
                        message: 'Home',
                    },
                    {
                        message: 'Rates',
                    },
                    {
                        message: 'Testimonials',
                    },
                    {
                        message: 'FAQ',
                    },
                    {
                        message: 'Blog',
                    },
                    {
                        message: 'Contact',
                    },

                ],
            }

        }
    }
</script>


<style scoped lang="scss">
    li {
        display: inline-block;
        font-weight: 600;
    }

    li:hover {
        cursor: pointer;
        color: #69bf14;
    }

    .align{
        vertical-align: middle;
    }

    .inline {
        display: inline-block;
    }

    .space {
        display: flex;
        justify-content: space-between;
    }

    .bg-image {
        background-image: url(../assets/avada-movers-homeherobackground-final.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        max-width: 100%;
        height: 650px;
    }

    .quote {
        color: white;
        background-color: #1975c0;
        border-radius: 40px;
        vertical-align: middle;
    }

    .head-text {
        text-align: center;
        padding-top: 11%;
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

    .bg-blue {
        background-color: #1975c0;
    }
</style>