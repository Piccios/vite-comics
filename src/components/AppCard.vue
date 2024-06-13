<script>
export default {
    data(){
        return{

        }
    }
}
</script>
<template>
    <section class="cards">
        <article class="comics" c-for="(card, index) in productsList" :key="index">
            <img :src="card.thumb" :alt="card.series">
        </article>
    </section>
</template>
<style scoped>
</style>