<template>
    <div class="newsCard">
        <img src="../assets/news-2.jpg" alt="">
        <p>{{newsText}}</p>
        <p>{{imageurl}}</p>
    </div>
</template>

<script>
export default {
    data() {
        return {
            imageurl: "../assets/news-2.jpg",
        }
    },

    props: {
        newsImage: String,
        newsText: String,
    },

}

</script>
<style lang="scss">
    .newsCard {
        height: 360px;
        padding: 2rem;
        position: relative;
        background-color: rgba(0, 0, 0, 0.5);
        
        .newsText {
            color: white;
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            text-align: center;
        }
    }

</style>
