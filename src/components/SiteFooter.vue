<template>
    <div class="footer">
        <div class="lg_container d-flex">
            <div class="col-3">
                <NexGen/>
                <p class="text-muted my-4">
                    A functional HTML Template for Corporate & Business.
                </p>
                <div>
                    <PhoneComponent
                    :contacts="contacts"
                    />
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import NexGen from './NexGen.vue';
import PhoneComponent from './PhoneComponent.vue';

export default {
    components: {
        NexGen,
        PhoneComponent,
    },

    props: {
        contacts: Object,
    }
}
</script>

<style lang="scss">

    @import '../assets/variables.scss';
    @import '../assets/common.scss';

    .footer {
        height: 680px;
        padding-top: 130px;
        background-image: url('../assets/img/bg-10.jpg');
        background-repeat: no-repeat;
        background-size: cover;
        background-position-y: center;
        color: $muted-grey;
    
    
    }

</style>