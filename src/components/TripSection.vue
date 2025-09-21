<script setup>
    import TripCard from './TripCard.vue';
    import CardImage1 from '../assets/sqare.svg';
    import CardImage2 from '../assets/swim.svg';
    import CardImage3 from '../assets/car.svg';
</script>

<template>
    <section class="trip">
        <div class="trip__left">
            <h6 class="trip__subtitle">Easy and Fast</h6>
            <h2 class="trip__title">Book your next trip in 3 easy steps</h2>
            <div class="trip__cards">
                <TripCard :image="CardImage1" title="Choose Destination" description="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Urna, tortor tempus."/>
                <TripCard :image="CardImage2" title="Make Payment" description="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Urna, tortor tempus."/>
                <TripCard :image="CardImage3" title="Reach Airport on Selected Date" description="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Urna, tortor tempus."/>
            </div>
        </div>
        <div class="trip__right"></div>
    </section>
</template>

<style scoped>
    .trip{
        margin-bottom: 12.5rem;
    }

    .trip__left{
        max-width: 31.9rem;
        width: 100%;
    }

    .trip__subtitle{
        font-family: Poppins;
        font-weight: 600;
        font-size: 1.125rem;
        color: #5E6282;
    }

    .trip__title{
        color: #14183E;
        font-family: Volkhov;
        font-weight: 700;
        font-size: 3.125rem;
    }

    .trip__cards{
        display: flex;
        flex-direction: column;
        gap: 3rem;
    }
</style>