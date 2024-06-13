<script>
export default {
    props: {
        products: {
        type: Array,
        required: true
        }
    }
}
</script>
<template>
    <section class="cards">
        <article class="card" v-for="(product, index) in productsList" :key="index">
            <img :src="product.thumb" :alt="product.series">
            <h4> 
                {{product.series}}
            </h4>
        </article>
    </section>
</template>
<style scoped>
    .cards {
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
    justify-content: center;
    padding: 1rem;
    background-color: black;    
    z-index: 1;
    position: relative;
    }

    .card {
    background: black;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    width: 200px;
    }

    .card img {
    width: 100%;
    height: auto;
    }
</style>