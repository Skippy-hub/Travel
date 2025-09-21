<script setup>
    import ServiceCard from './ServiceCard.vue';
    import CardImage1 from '../assets/Group1000001925.svg';
    import CardImage2 from '../assets/Group51.svg';
    import CardImage3 from '../assets/Group50.svg';
    import CardImage4 from '../assets/Group49.svg';
</script>

<template>
    <section class="services">
        <div class="services__top">
            <h6 class="services__subtitle">CATEGORY</h6>
            <h2 class="services__title">We Offer Best Services</h2>
        </div>
        <div class="services__cards">
            <ServiceCard :image="CardImage1" title="Calculated Weather" description="Built Wicket longer admire do barton vanity itself do in it."/>
            <ServiceCard :image="CardImage2" title="Best Flights" description="Engrossed listening. Park gate sell they west hard for the."/>
            <ServiceCard :image="CardImage3" title="Local Events" description="Barton vanity itself do in it. Preferd to men it engrossed listening."/>
            <ServiceCard :image="CardImage4" title="Customization" description="We deliver outsourced aviation services for military customers"/>
        </div>
    </section>
</template>

<style scoped>
    .services{
        margin-bottom: 7.75rem;
        text-align: center;
    }

    .services__top{
        display: flex;
        flex-direction: column;
        gap: 0.625rem;
        margin-bottom: 3.25rem;
    }

    .services__top-subtitle{
        color: #5E6282;
        font-size: 1.125rem;
        font-weight: 600;
        font-family: Poppins;
        line-height: 150%;
    }

    .services__top-title{
        font-family: Volkhov;
        font-weight: 700;
        font-size: 3.125rem;
        color: #14183E;
        line-height: 130%;
    }

    .services__cards{
        display: flex;
        justify-content: space-between;
        gap: 1rem;
    }
</style>