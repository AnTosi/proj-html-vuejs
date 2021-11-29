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
                    <p class="mt-3">
                        For 20 years working with the most innovative in the field of transport
                    </p>

                    <button class="green">GET IN TOUCH</button>
                    <button class="transparent mx-4">READ MORE</button>
                </div>
            </div>
        </section>

        <!-- //here ends the section one, the one with the jumbotron -->

        <!-- section 2 -->

        <section class="two">
            <div class="lg_container d-flex">
                <div class="col-4 height_420">
                    <div class="px-3">
                        <span class="pre_title">OUR BUSINESS AREAS</span>
                        <h3 class="superbold my-4">
                            Logistics Services
                        </h3>

                        <p class="text-muted mb-3 pr-4">
                            We are leaders in providing logistics services with a set of cutting edge technologies and a team of experienced and renowned professionals.
                        </p>

                        <div>
                            <span class="green_on_green p-2">Tradition</span>
                            <span class="green_on_green p-2 mx-3">Quality</span>
                            <span class="green_on_green p-2">Security</span>
                        </div>

                        <button class="green mt-4">
                            READ MORE
                        </button>
                    </div>
                </div>

                <div class="height_420 col-4 px-2">
                    <div class="cards">
                        <img src="../assets/img/gallery-3.jpg" alt="hands holding a paper with coloured charts and a phone with the same charts">
                        <h4 class="py-3 fw-600">Technology</h4>
                        <p class="text-muted mb-0">Focused on developing technology solutions adapted to our client's needs.</p>
                    </div>
                </div>

                <div class="height_420 col-4 px-2">
                    <div class="cards">
                        <img src="../assets/img/gallery-5.jpg" alt="dude closing a box with scotch tape">
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

        <!-- //section 2 -->

        <!-- section 3 -->

        <section class="three">
            <div class="left_container">
                <span class="pre_title">
                    ABOUT THE NETWORK
                </span>
                <h3 class="superbold text-white my-4">
                    <span class="superbold text-white highlighted px-2">The</span>
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
                <img src="../assets/img/about-5.jpg" alt="huge building with glass wall, picture taken from below with a cool angle">
            </div>
            <div class="sm_circles_container d-flex flex-wrap">
                <span class="sm_circle mx-1" v-for="index in 36" :key="index"></span>
            </div>
        </section>

        <!-- //section 3 -->

        <!-- section 4 -->

        <section class="four">
            <div class="lg_container d-flex align-items-center justify-content-around">
                <img src="../assets/img/logo-5.png" alt="less logo, less written within curly brackets">

                <img src="../assets/img/logo-1.png" alt="woocommerce logo,woocommerce written with woo in a speech bubble">

                <img src="../assets/img/logo-2.png" alt="pingdom logo, pingdom written with a rounded font">

                <img src="../assets/img/logo-3.png" alt="jQuery logo, jQuery written in italic">

                <img src="../assets/img/logo-4.png" alt="">
                
                <img src="../assets/img/logo-5.png" alt="less logo, less written within curly brackets">
            
            </div>
        </section>

        <!-- //section 4 -->

        <!-- section 5 -->

        <section class="five">
            <div class="lg_container">
                <span class="pre_title">
                    OUR EDITORIAL CONTENT
                </span>
                <h3 class="superbold text-black mt-4 mb-5">
                    Latest
                    <span class="green_on_green superbold px-2"> News</span>
                </h3>
                <div class="d-flex justify-content-between  align-items-end">
                    <p class="text-muted mb-0">Every week we publish content about what is best in the business world.</p>
                    <button class="green">SEE ALL</button>
                </div>

                <div class="news_container d-flex justify-content-around mt-5">
                    <div class="col-4 px-3">
                        <!-- <img src="../assets/img/news-2.jpg" alt=""> -->                   
                        <NewsCard
                        :newsImage="news[0].image"
                        :newsText="news[0].text"
                        />
                    </div>
                    <div class="col-4 px-3">
                        <NewsCard
                        :newsImage="news[1].image"
                        :newsText="news[1].text"
                        />
                    </div>
                    <div class="col-4 px-3">
                        <NewsCard
                        :newsImage="news[2].image"
                        :newsText="news[2].text"
                        />
                    </div>
                </div>
            </div>

        </section>

        <!-- //section 5 -->


        <section class="six">
            <div class="sm_container d-flex">
                <div class="left col-6">
                    <span class="pre_title">NEWSLETTER</span>
                    <h3 class="superbold text-white my-4">
                        <span class="superbold text-white highlighted px-3">Know</span>
                        First
                    </h3>
                    <p class="text_lightgrey mb-5 pr-4">
                        Follow closely and receive content about our company and the news of the current market.
                    </p>              
                </div>

                <div class="right col-6">
                    <input type="text" placeholder="Name">
                    <input type="text" placeholder="Email">
                    <button class="green">SUBSCRIBE</button>
                </div>

            </div>
        </section>

        <!-- //section 6 -->

        <!-- section 7 -->

        <section class="seven">
            <div class="lg_container d-flex">
                <div class="left col-8">
                    <span class="pre_title">SEND A MESSAGE</span>
                    <h3 class="superbold text-black mt-4 mb-4">
                        Get in 
                        <span class="green_on_green superbold px-2"> Touch</span>
                    </h3>
                    <p class="text-muted">
                        We will respond to your message as soon as possible.
                    </p>

                    <div class="form_container d-flex flex-wrap">
                        <div class="col-6 input_container p-2"><input type="text" class="form_item" placeholder="Name"></div>
                        <div class="col-6 input_container p-2"><input type="text" class="form_item" placeholder="Email"></div>
                        <div class="col-6 input_container p-2"><input type="text" class="form_item" placeholder="Phone"></div>
                        <div class="col-6 input_container p-2">
                            <select name="More Info" id="MoreInfo" class="form_item text-muted">
                                <option value="More Info">More Info</option>
                            </select>            
                        </div>
                        <div class="col-12 input_container p-2"><textarea name="Message" id="Message" cols="30" rows="10" placeholder="Message" class="form_item"></textarea></div>
                        <button class="green mt-4 mx-2">SEND</button>
                    </div>
                </div>

                <div class="right pl-4"> 
                    <h5 class="bold">
                        Example Inc.
                    </h5>

                    <p class="my-3 text-muted">
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                    </p>
                    <p class="my-3 text-muted">
                        Eum autem reprehenderit quos libero harum laudantium mollitia?
                    </p>
                    
                    <div class="text-green">
                        <div class="py-2">
                            <PhoneComponent
                            :contacts="contacts"
                            />
                        </div>
                        <div class="py-2">
                            <MailComponent
                            :contacts="contacts"
                            />
                        </div>
                        <div class="py-2">
                            <AddressComponent
                            :contacts="contacts"
                            />
                        </div>
                        <button class="transparent text-green mt-3">VIEW MAP</button>
                    </div>

                </div>
            </div>
        </section>

        <section class="eight">
        
        </section> 
    </main>
    
</template>

<script>
import NewsCard from './NewsCard.vue';
import PhoneComponent from './PhoneComponent.vue';
import MailComponent from './MailComponent.vue';
import AddressComponent from './AddressComponent.vue';

export default {
  components: { 
      NewsCard,
      PhoneComponent,
      MailComponent,
    AddressComponent

    },

    props: {
        "contacts": Object,
    },

    data() {
        return {
            news: [
                {
                    image: "news-1",
                    text: "Increasing creativity is possible for everyone"
                },
                {
                    image: 'news-2',
                    text: "Because market research is bart of the business plan"
                },

                {
                    image: "news-3",
                    text: "Working from home is now a trend"
                },

                {
                    image: "news-4",
                    text: ""
                },

                {
                    image:"news-5",
                    text: ""
                }

            ] 
        }
    }
    
}
</script>

<style lang="scss">

@import '../assets/common.scss';
@import '../assets/variables.scss';

    .jumbosection {
        background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url("../assets/img/jumbo.jpg");
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
                padding-right: 2rem;
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
            padding: 115px 0;
            background-color: $black;
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
            padding: 115px 0;
            background-color: $bg-superlight-green;

            img {
                opacity: 0.5;
            }

        }

        &.five {
            padding: 115px 0;
            
            .news_container {
                margin-right: -1rem;
                margin-left: -1rem;
            }
        }

        &.six {
            padding: 115px 0;
            background-image: url('../assets/img/bg-1.jpg');
            height: 455px;
            background-repeat: no-repeat;
            background-size: cover;
            background-position-y: 50%;
            input {
                width: 90%;
                margin: auto;
                background-color: rgba(255, 255, 255, 0.568);
                border: none;
                border-radius: 5px;
                height: 3rem;
                margin-bottom: 20px;
                padding: 1rem;
            }
        }

        &.seven {
            padding: 120px 0;
            background-color: $bg-superlight-green;

            .form_item{
                width: 100%;
                background-color: #7373732d;
                border-radius: 5px;
                border: none;
                padding: 1rem;
            }

            input {

                height: 3rem;
                
            }

            select {
                height: 3rem;
            }

            textarea {
                resize: none;
            }
            .contact_component {
                padding-left: 0 !important;
                padding-right: 0 !important;
                width: 100%;
            }

            span.icon {
                display: flex;
                background-color: $bg-light-green;
                padding: 1rem;
                color: $main-dark-green;
                height: 45px;
                width: 45px;
                border-radius: 50%;
                align-items: center;
                justify-content: center;
                font-size: 1.2rem;  
                margin-right: 1rem;
            }


        }
    }

</style>