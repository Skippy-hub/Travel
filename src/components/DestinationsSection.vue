<script setup>
    import DestinationCard from './DestinationCard.vue';
    import CardImage1 from '../assets/Rome.png';
    import CardImage2 from '../assets/London.png';
    import CardImage3 from '../assets/Europe.png';
</script>

<template>
    <section class="destination">
        <div class="destination__top">
            <h6 class="destination__subtitle">Top Selling</h6>
            <h2 class="destination__title">Top Destinations</h2>
        </div>
        <div class="destination__cards">
            <DestinationCard :image="CardImage1" title="Rome, Italty" price="5.42" days="10"/>
            <DestinationCard :image="CardImage2" title="London, UK" price="4.2" days="12"/>
            <DestinationCard :image="CardImage3" title="Full Europe" price="15" days="28"/>
        </div>
    </section>
</template>

<style scoped>
    .destination{
        margin-bottom: 11.625rem;
        text-align: center;
    }
    
    .destination__top{
        display: flex;
        flex-direction: column;
        gap: 0.625rem;
        margin-bottom: 3.25rem;
    }

    .destination__subtitle{
        font-family: Poppins;
        font-weight: 600;
        font-size: 1.125rem;
        color: #5E6282;
    }

    .destination__title{
        font-family: Volkhov;
        font-weight: 700;
        color: #14183E;
        font-size: 3.125rem;
    }

    .destination__cards{
        display: flex;
        justify-content: space-between;
        gap: 1rem;
    }
</style>