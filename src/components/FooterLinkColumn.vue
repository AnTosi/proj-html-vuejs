<template>
    <div class="d-flex col-12">
        <div v-for="(footerLinkColumn, index) in footerLinksColumns" :key="`footerLinkColumn` + index" class="col-4 p-2">
            <div class="footer_link_column">
                <h3 class="mb-3">
                    {{footerLinkColumn.title}} 
                </h3>
                <ul>
                    <li v-for="(link, index) in footerLinkColumn.links" :key="`footerLink` + index" class="py-1">
                        <i class="fas fa-chevron-right pr-2"></i> {{link}}
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    props: {
        footerLinksColumns: Array,
    }
}
</script>

<style lang="scss">

    .footer_link_column {
        padding: 4rem 2rem;
        border-radius: 0.75rem;
        background-color: rgba(255, 255, 255, 0.075);

        h3 {
            font-weight: 700;
            color: white;
        }

        ul {
            padding-left: 0 !important;

            li {
                list-style: none;
            }

            .pr-2 {
                padding-right: 0.75rem;
            }
        }
    }
</style>