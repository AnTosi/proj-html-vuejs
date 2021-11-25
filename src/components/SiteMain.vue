<template>
    <main>
        <section class="one jumbosection">
            <div class="lg_container position-relative">
                <div class="jumbotext text-white">
                    <span class="title">
                        <span class="underline">
                        </span>
                        Logistics that goes further.
                    </span>
                    <p class="mt-3">
                        For 20 years working with the most innovative in the field of transport
                    </p>

                    <button class="green">GET IN TOUCH</button>
                    <button class="transparent mx-4">READ MORE</button>
                </div>
            </div>
        </section>

        <section class="two">

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
            width: 45%;
            text-align: left;
            z-index: 5;
            color: white;

            .title {
                position: relative;
                font-family: 'Poppins', sans-serif;
                font-weight: 900;
                font-size: 5rem;
                line-height: 6rem;
            }

            .underline {
                display: inline-block;
                position: absolute;
                background-color: #08a0a0b6;
                width: 100%;
                height: 2.5rem;
                top: 3.5rem;
                z-index: -1;
            }

            p {
                color: $muted-grey;
            }

            button {
                padding-left: 1rem;
                padding-right: 1rem;
                padding-top: 0.5rem;
                padding-bottom: 0.5rem;              
                border-radius: 5px;
                color: white;
                border: 1px solid #058283;
            
                &.green {
                    background-color: #058283;
                    
                }

                &.transparent {
                    background-color: transparent;
                }
            }
        }
    }

</style>