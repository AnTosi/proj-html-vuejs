<template>
    <span class="phoneComponent contact_component px-3 d-flex align-items-center">
        <span class="icon">
            <i class="fas fa-map-marker-alt"></i>
        </span>                  
        <a href="#">{{contacts.address}}</a>
    </span>
</template>

<script>
export default {
    props: {
        "contacts": Object,
    }
}
</script>