<template>
    <div class="header debug">
        <div class="lg_container debug d-flex align-items-center justify-content-between">
            <div>
                <i class="fas fa-clock p-2"></i>Open Hours: {{openTime.openingDay}} - {{openTime.closingDay}} - {{openTime.openingHour}} - {{openTime.closingHour}}
            </div>
            <div class="contacts">

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
    </div>
</template>

<script>
import MailComponent from './MailComponent.vue';
import PhoneComponent from './PhoneComponent.vue';

export default {
  components: { 
        PhoneComponent,
        MailComponent 
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

    .header {
        width: 100%;
        background-color: #21333E;
        height: 35px;
        color: $muted-grey;
        font-size: 0.8rem;
    }

    .lg_container {
        width: 62%;
        margin: auto;
        height: 100%;
        // color: ;
    
    } 
</style>