<template>
    <div class="footer">
        <div class="lg_container d-flex">
            <div class="col-3">
                <NexGen/>
                <p class="text-muted my-4 pb-2">
                    A functional HTML Template for Corporate & Business.
                </p>
                <div>
                    <div>
                        <PhoneComponent
                        :contacts="contacts"
                        />
                    </div>
                    <div class="my-3">
                        <MailComponent
                        :contacts="contacts"
                        />
                    </div>
                    <div class="mb-4">
                        <AddressComponent
                        :contacts="contacts"
                        />
                    </div>
                    <button class="transparent">GET IN TOUCH</button>
                </div>
            </div>
            <div class="col-9 d-flex">
                <FooterLinkColumn
                :footerLinksColumns="footerLinksColumns"
                />
            </div>
        </div>
        <div class="bottom_page">
            <div class="lg_container d-flex justify-content-between">
                <div>Enjoy the low price. We are tracking any intention of piracy.</div>
                <div><i class="far fa-copyright"></i> 2020 NEXGEN is Proudly Powered by <span class="text-green">Codings.</span></div>
            </div>
        </div>
    </div>
</template>

<script>
import AddressComponent from './AddressComponent.vue';
import FooterLinkColumn from './FooterLinkColumn.vue';
import MailComponent from './MailComponent.vue';
import NexGen from './NexGen.vue';
import PhoneComponent from './PhoneComponent.vue';

export default {
    components: {
        NexGen,
        PhoneComponent,
        MailComponent,
        AddressComponent,
        FooterLinkColumn
    },

    props: {
            contacts: Object,
    },

    data() {
        return {
            footerLinksColumns: [
                {
                    title: "About",
                    links: ["The Company", "Institutional", "Social & Events", "Innovation", "Environment", "Technology",],
                },

                {
                    title: "Transport",
                    links: ["Industrialized", "Chemicals", "Packaged Liquids", "Construction", "Laminated Wood", "And others"],
                },

                {
                    title: "Support",
                    links: ["Responsibility", "Terms of Use", "About Cookies", "Privacy Policy", "Accessibility", "Information"],
                }

                
            ]
        }
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

        span.component {
            padding-left: 0 !important;
        }
    
        .bottom_page {
            background-color: #0D0D11;
        }
    }

</style>