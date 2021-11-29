<template>
    <span class="mailComponent contact_component px-3 d-flex align-items-center">                   
        <span class="icon">
            <i class="fas fa-envelope px-2"></i>
        </span>
        <a href="#">{{contacts.mailAddress}}</a>
    </span>
</template>

<script>
export default {
    props: {
        "contacts": Object,
    }
}
</script>