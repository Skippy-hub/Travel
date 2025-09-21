<script setup>

</script>

<template>
    <section class="hero">
        <div class="hero__content">
            <h6 class="hero__content-subtitle">Best Destinations around the world</h6>
            <h1 class="hero__content-title">Travel, enjoy and live a new and full life</h1>
            <p class="hero__content-description">Built Wicket longer admire do barton vanity itself do in it. Preferred to sportsmen it engrossed listening. Park gate sell they west hard for the.</p>
            <div class="hero__content-buttons">
                <button class="buttons__button">Find out more</button>
                <div class="buttons__demoBlock">
                    <button class="demoBlock__play"><img class="demoBlock__img" src="../assets/hero-play.svg" alt=""></button>
                    <p class="demoBlock__text">Play Demo</p>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
    .hero{
        background: url("../assets/hero-img.png") no-repeat right;
        padding: 7rem 0 7.3125rem;
        margin-bottom: 6rem;
    }

    .hero__content{
        max-width: 39.375rem;
        width: 100%;
        display: flex;
        flex-direction: column;
        gap: 1.75rem;
    }

    .hero__content-subtitle{
        font-family: Poppins;
        font-weight: 700;
        font-size: 1.25rem;
        text-transform: uppercase;
        color: #DF6951;
    }

    .hero__content-title{
        font-family: Volkhov;
        font-weight: 700;
        font-size: 5.25rem;
        line-height: 89px;
        letter-spacing: -4%;
        color: #181E4B;
    }

    .hero__content-description{
        color: #5E6282;
        font-family: Poppins;
        line-height: 30px;
        max-width: 29.8rem;
        width: 100%;
    }

    .hero__content-buttons{
        display: flex;
        max-width: 23.7rem;
        width: 100%;
        justify-content: space-between;
        gap: 1rem;
        align-items: center;
    }

    .buttons__button{
        padding: 1.125rem 1.625rem;
        background: #F1A501;
        box-shadow: 0px 20px 35px 0px #F1A50126;
        border-radius: 0.625rem;
        border: none;
        color: #fff;
        font-family: Google Sans;
        font-weight: 500;
        font-size: 1.125rem;
        text-align: center;
        cursor: pointer;
    }

    .buttons__demoBlock{
        display: flex;
        gap: 1.3rem;
        align-items: center;
    }
    
    .demoBlock__play{
        border-radius: 50%;
        border: none;
        background: #DF6951;
        box-shadow: 0px 15px 30px 0px #DF69514D;
        width: 3.25rem;
        height: 3.25rem;
        cursor: pointer;
    }

    .demoBlock__text{
        color: #686D77;
        font-family: Poppins;
        font-size: 1.0625rem;
        white-space: nowrap;
    }
</style>