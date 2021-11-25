<template>
    <main>

        <!-- here start the section one, the one with the jumbotron -->

        <section class="one jumbosection">
            <div class="lg_container position-relative">
                <div class="jumbotext text-white">
                    <span class="title superbold">
                        <span class="underline">
                        </span>
                        Logistics that goes further.
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

        </section>

        <section class="three">

        </section>

        <section class="four">

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
                width: 100%;
                height: 2rem;
                top: 2.7rem;
                z-index: -1;
            }

            p {
                color: $muted-grey;
                font-size: 1.2rem;
                padding-right: 5rem;
                padding-bottom: 2rem;
            }

            
        }
    }

    section.two {
        height: 730px;
        background-color: #EEF4ED;
        padding: 120px 1rem;

        h3 {
            font-size: 3rem;
        }

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

</style>