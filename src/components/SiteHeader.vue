<template>
    <div class="header">

        <!-- header top, contacts area -->

        <div class="lg_container d-flex align-items-center justify-content-between">
            <div>
                <i class="fas fa-clock p-2"></i>Open Hours: {{openTime.openingDay}} - {{openTime.closingDay}} - {{openTime.openingHour}} - {{openTime.closingHour}}
            </div>
            <div class="contacts d-flex">

                <PhoneComponent
                :contacts="contacts"
                />

                <MailComponent
                :contacts="contacts"
                />

                <a href="#"><i class="fab fa-facebook-f px-3"></i></a>
                <a href=""><i class="fab fa-twitter px-3" aria-hidden="true"></i></a>
                <a href="#"><i class="fab fa-linkedin-in px-3"></i></a>
            </div>
        </div>

        <!-- //header top, contacts area -->

        <!-- header bottom, nav area -->
        
        <nav class="lg_container mt-3 d-flex justify-content-between">
            <div class="nav_left">
                <NexGen/>
            </div>

            <div class="nav_right">
                <ul class="d-flex text-white condensed600">
                    <li>HOME</li>
                    <li>SERVICES</li>
                    <li>SKILLS</li>
                    <li>PARTNERS</li>
                    <li>BLOG</li>
                    <li class="active">GET IN TOUCH</li>
                </ul>
            </div>
        </nav>
        
        <!-- //header bottom, nav area -->

    </div>
</template>

<script>
import MailComponent from './MailComponent.vue';
import NexGen from './NexGen.vue';
import PhoneComponent from './PhoneComponent.vue';

export default {
  components: { 
        PhoneComponent,
        MailComponent,
        NexGen 
    },
    
    name: 'SiteHeader',
    props: {
        openTime: Object,
        contacts: Object
    },
}

</script>

<style lang="scss">

    @import '../assets/variables.scss';
    @import '../assets/common.scss';

    .header {
        width: 100%;
        background-color: #21333E;
        color: $muted-grey;
        font-size: 0.8rem;
        z-index: 3;
        position: absolute;
        height: 35px;
        top: 0;
        left: 0;

        .nav_right {
            font-size: 1rem;
            li {
                list-style: none;
                margin-left: 1.3rem;
                margin-right: 1.3rem;
                padding-top: 0.5rem;
                padding-bottom: 0.5rem;
                
                &.active {
                    // background-color: #048383;
                    background-color: #E94649;
                    border-radius: 4px;
                    border: 1px solid $main-red;
                    padding-left: 1rem;
                    padding-right: 1rem;
                    &:hover{
                        border: 1px solid $main-red;
                    }
                }
                &:hover {
                    cursor: pointer;
                    border-bottom: 2px solid $main-red;
                }
            }
        }

        
    }
</style>