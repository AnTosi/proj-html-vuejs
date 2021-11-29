<template>
    <div class="footer">
        <div class="lg_container">
            <NexGen/>
        </div>
    </div>
</template>

<script>
import NexGen from './NexGen.vue';

export default {
    components: {
        NexGen,
    }    
}
</script>

<style lang="scss">
    .footer {
        height: 680px;
        padding-top: 130px;
        background-image: url('../assets/img/bg-10.jpg');
        background-repeat: no-repeat;
        background-size: cover;
        background-position-y: center;
    
    
    }

</style>