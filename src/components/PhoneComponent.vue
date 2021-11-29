<template>
    <span class="phoneComponent contact_component px-3 d-flex align-items-center">
        <span class="icon">
            <i class="fas fa-phone px-2"></i>
        </span>                 
        <a href="#">{{contacts.phoneNumber}}</a>
    </span>
</template>

<script>
export default {
    props: {
        contacts: Object,
    }
}
</script>