<template>
    <span class="phoneComponent px-3">                   
        <i class="fas fa-phone px-2"></i>
        <a href="#">{{contacts.phoneNumber}}</a>
    </span>
</template>

<script>
export default {
    props: {
        "contacts": Object,
    }
}
</script>