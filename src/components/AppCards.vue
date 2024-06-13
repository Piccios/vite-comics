<script>
import AppCard from "./AppCard.vue"
export default {
    data(){
        return {

        }
    }, 
    props: {
        
    },
    methods:{
        getImagePath: function(img) {

        }
    }
}
</script>

<template>
    <section id="jumbotron">
        <div class="currentSeries">
            <h2>CURRENT SERIES</h2>
        </div>
    </section>

    <section id="cards">
        <p>
            {{ messaggio }}
        </p>

    </section>
</template>

<style scoped>

    section#jumbotron{
        width: 100%;
        height: 550px;
        background-image: url(../assets/img/jumbotron.jpg);
        background-size: cover;
    }

    div.currentSeries{
        background-color: rgb(2, 130, 249);
        color: white;
        padding: .66rem 1rem;
        width: 250px;
        position: absolute;
        left: 250px;
        top: 695px;
        text-align: center;
    }
    
    section#cards{
        
        height: 650px;
        width: 100%;
        background-color: rgb(28, 28, 28);
    }


</style>