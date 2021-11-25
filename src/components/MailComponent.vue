<template>
    <span class="mailComponent px-3">                   
        <i class="fas fa-envelope px-2"></i>
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