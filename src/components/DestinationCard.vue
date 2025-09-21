<script setup>
    const props = defineProps({
        image: String,
        title: String,
        price: Number,
        days: Number
    });
</script>

<template>
    <div class="destination__card">
        <img :src="props.image" alt="">
        <div class="destination__container">
            <div class="destination__card-top">
                <p class="destination__card-title">{{ props.title }}</p>
                <p class="destination__card-price">${{ props.price }}k</p>
            </div>
            <p class="destination__card-daysTrip">{{ props.days }} Days Trip</p>
        </div>
    </div>
</template>

<style scoped>
    .destination__card{
        position: relative;
        max-width: 19.5rem;
        width: 100%;
        border-radius: 1.5rem;
        text-align-last: left;
        box-shadow: 0px 1.85px 3.15px 0px #00000050;
        color: #5E6282;
        line-height: 125%;
    }

    .destination__container{
        position: absolute;
        bottom: 0;
        background: #fff;
        left: 0;
        right: 0;
        padding: 1.6875rem 1.5625rem 2.625rem 1.25rem;
    }

    .destination__card-top{
        display: flex;
        justify-content: space-between;
        margin-bottom: 1.1875rem;
        font-size: 1.125rem;
    }
</style>