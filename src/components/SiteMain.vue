<template>
    <main>

        <!-- here start the section one, the one with the jumbotron -->

        <section class="one jumbosection">
            <div class="lg_container position-relative">
                <div class="jumbotext text-white">
                    <span class="title superbold">
                        <span class="position-relative title superbold">
                            Logistics
                            <span class="underline"></span>
                        </span>
                         that goes further.
                    </span>
                    <p class="mt-3 pr-5">
                        For 20 years working with the most innovative in the field of transport
                    </p>

                    <button class="green">GET IN TOUCH</button>
                    <button class="transparent mx-4">READ MORE</button>
                </div>
            </div>
        </section>

        <!-- //here ends the section one, the one with the jumbotron -->

        <section class="two">
            <div class="lg_container d-flex">
                <div class="col-4 height_420">
                    <div class="px-3">
                        <span class="text-green condensed">OUR BUSINESS AREAS</span>
                        <h3 class="superbold my-4">
                            Logistics Services
                        </h3>

                        <p class="text-muted mb-3 pr-4">
                            We are leaders in providing logistics services with a set of cutting edge technologies and a team of experienced and renowned professionals.
                        </p>

                        <div>
                            <span class="bg_green p-2">Tradition</span>
                            <span class="bg_green p-2 mx-3">Quality</span>
                            <span class="bg_green p-2">Security</span>
                        </div>

                        <button class="green mt-4">
                            READ MORE
                        </button>
                    </div>
                </div>

                <div class="height_420 col-4 px-2">
                    <div class="cards">
                        <img src="../assets/gallery-3.jpg" alt="hands holding a paper with coloured charts and a phone with the same charts">
                        <h4 class="py-3 fw-600">Technology</h4>
                        <p class="text-muted mb-0">Focused on developing technology solutions adapted to our client's needs.</p>
                    </div>
                </div>

                <div class="height_420 col-4 px-2">
                    <div class="cards">
                        <img src="../assets/gallery-5.jpg" alt="dude closing a box with scotch tape">
                        <h4 class="py-3 fw-600">Transport</h4>
                        <p class="text-muted mb-0">
                            We develop operational strategies to improve logistical efficiency.
                        </p>
                    </div>
                </div>
            </div>

            <div class="sm_circles_container d-flex flex-wrap">
                <span class="sm_circle mx-1" v-for="index in 36" :key="index"></span>
            </div>
        </section>

        <section class="three">
            <div class="left_container">
                <span class="text-green condensed">
                    ABOUT THE NETWORK
                </span>
                <h3 class="superbold text-white my-4">
                    <span class="superbold text-white highlighted">The</span>
                    Company
                </h3>
                <p class="text-muted mb-5">
                    With all of this expertise and capability comes an unrivalled commitment to customer service.
                </p>

                <div class="d-flex align-items-center mb-5 pt-5">
                    <span class="grey_circle_border col-3 bold text-muted">
                        <span class="text_lightgrey">
                            <span class="font_size_3">0</span>%
                        </span>
                    </span>
                    <div class="col-9">
                        <h4 class="bold mb-3 text-white">Leadership</h4>
                        <p class="text-muted mb-0">Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>

                <div class="d-flex align-items-center pt-4 mb-5">
                    <span class="grey_circle_border col-3 bold text-muted">
                        <span class="text_lightgrey">
                            <span class="font_size_3">0</span>%
                        </span>
                    </span>
                    <div class="col-9">
                        <h4 class="bold mb-3 text-white">Psychology</h4>
                        <p class="text-muted mb-0">Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>

                <div class="d-flex align-items-center pt-4 mb-5">
                    <span class="grey_circle_border col-3 bold text-muted">
                        <span class="completion_1percent"></span>
                        <span class="text_lightgrey">
                            <span class="font_size_3">1</span>%
                        </span>
                    </span>
                    <div class="col-9">
                        <h4 class="bold mb-3 text-white">Flexibility</h4>
                        <p class="text-muted mb-0">Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>

            </div>
            <div class="pic_right">
                <img src="../assets/about-5.jpg" alt="huge building with glass wall, picture taken from below with a cool angle">
            </div>
            <div class="sm_circles_container d-flex flex-wrap">
                <span class="sm_circle mx-1" v-for="index in 36" :key="index"></span>
            </div>
        </section>

        <section class="four">
            <div class="lg_container d-flex align-items-center justify-content-around">
                <img src="../assets/logo-5.png" alt="less logo, less written between curly brackets">

                <img src="../assets/logo-1.png" alt="">

                <img src="../assets/logo-2.png" alt="">

                <img src="../assets/logo-3.png" alt="">

                <img src="../assets/logo-4.png" alt="">
                
                <img src="../assets/logo-5.png" alt="">
            
            </div>
        </section>

        <section class="five">

        </section>

        <section class="six">

        </section>

        <section class="seven">

        </section>

        <section class="eight">
        
        </section> 
    </main>
    
</template>

<script>
export default {
    
}
</script>

<style lang="scss">

@import '../assets/common.scss';
@import '../assets/variables.scss';

    .jumbosection {
        background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url("../assets/jumbo.jpg");
        height: 862px;
        background-position-y: 100%;
        background-repeat: no-repeat;
        background-size: cover;

        .jumbotext {
            position: absolute;
            top: 40%;
            right: 10%;
            width: 40%;
            text-align: left;
            z-index: 5;
            color: white;

            .title {
                position: relative;
                font-size: 4rem;
                line-height: 5rem;
            }

            .underline {
                display: inline-block;
                position: absolute;
                background-color: #08a0a0b6;
                width: 98%;
                height: 2rem;
                top: 2.7rem;
                left: 0;
                z-index: -1;
                opacity: 0.6;
            }

            p {
                color: $muted-grey;
                font-size: 1.2rem;
                padding-right: 5rem;
                padding-bottom: 2rem;
            }

            
        }
    }

    section {
        h3 {
            font-size: 3rem;
        }
        &.two {
            height: 730px;
            background-color: $bg-superlight-green;
            padding: 120px 1rem;
            position: relative;

            p.pr-4 {
                padding-right: 2rem;
            } 

            span.bg_green {
                color: $main-dark-green;
                border-radius: 3px;
            }

            .cards {
                background-color: white;
                padding: 15% 15%;
                border-radius: 0.5rem;
                height: 420px;

                img {
                    // height: 165px;
                    width: 100%;
                }

                h4 {
                    font-size: 1.6rem;
                }
            }
        }

        &.three {
            padding: 120px 0;
            background-color: black;
            position:relative;

            .pic_right {
                width: 50%;
                position: absolute;
                top: 0;
                right: 0;
                height: 100%;
                text-align: right;
                img {
                    height: 100%;
                    width: 100%;
                    object-fit: cover;
                }
            }
        }

        &.four {
            padding: 100px 0;
            background-color: $bg-superlight-green;

            img {
                opacity: 0.5;
            }

        } 
    }

</style>