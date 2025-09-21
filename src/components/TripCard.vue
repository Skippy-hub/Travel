<script setup>
    const props = defineProps({
        image: String,
        title: String,
        description: String
    });
</script>

<template>
    <div class="trip__card">
        <img :src="props.image" alt="">
        <div class="card__content">
            <h6 class="card__title">{{ props.title }}</h6>
            <p class="card__description">{{ props.description }}</p>
        </div>
    </div>
</template>

<style scoped>
    .trip__card{
        max-width: 24.6875rem;
        width: 100%;
        display: flex;
        gap: 1.3125rem;
        align-items: center;
    }

    .card__content{
        color: #5E6282;
        line-height: 125%;
        font-family: Poppins, sans-serif;
    }

    .card__title{
        font-weight: 700;
    }
</style>