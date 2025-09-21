<script setup>
    const props = defineProps({
        image: String,
        title: String,
        description: String
    });
</script>

<template>
    <div class="services__card">
        <img class="services__card-img" :src="props.image" alt="">
        <h6 class="services__card-title">{{props.title}}</h6>
        <p class="services__card-description">{{ props.description }}</p>
    </div>
</template>

<style scoped>
    .services__card{
        display: flex;
        flex-direction: column;
        gap: 1rem;
        padding: 2rem 0.75rem 1.75rem;
        border-radius: 2.25rem;
        max-width: 12.75rem;
        width: 100%;
        align-items: center;
    }

    .services__card:hover{
        box-shadow: 0px 1.85px 3.15px 0px #111;
    }

    .services__card-img{
        width: 7.5rem;
    }

    .services__card-title{
        font-family: Open Sans;
        font-weight: 600;
        font-size: 1.25rem;
        color: #1E1D4C;
    }

    .services__card-description{
        color: #5E6282;
        font-size: 1rem;
    }
</style>