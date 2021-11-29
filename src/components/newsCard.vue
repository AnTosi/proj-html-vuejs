<template>
    <div class="newsCard">
        <img :src="`img/`+newsImage+`.jpg`" alt class="icon" />
        <p class="newsText">{{newsText}}</p>
    </div>
</template>

<script>
export default {
       props: {
        newsImage: String,
        newsText: String,
    },

}

</script>
<style lang="scss">
    .newsCard {
        height: 360px;
        position: relative;
        background-color: rgb(0, 0, 0);
        border-radius: 0.5rem;
        
        .newsText {
            color: white;
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            text-align: center;
            padding: 0 1rem 2rem 1rem;
            font-weight: 700;
            font-size: 1.5rem;
            
        }

        img {
            object-fit: cover;
            width: 100%;
            height: 100%;
            border-radius: 0.5rem;
            opacity: 0.65;
        }
    }

</style>
