<script setup>

</script>

<template>
    <nav class="nav">
        <a class="nav__logo" href="#">
            <img class="nav__logo-img" src="../assets/Logo.svg" alt=""/>
        </a>
        <div class="nav__right">
            <ul class="nav__list">
                <li class="nav__list-item">Desitnations</li>
                <li class="nav__list-item">Hotels</li>
                <li class="nav__list-item">Flights</li>
                <li class="nav__list-item">Bookings</li>
            </ul>
            <div class="nav__buttons">
                <button class="nav__button">Login</button>
                <button class="nav__button nav__button--singup">Sign up</button>
            </div>
            <div class="nav__lang">EN</div>
        </div>
    </nav>
</template>

<style scoped>
    .nav{
        color: #212832;
        display: flex;
        justify-content: space-between;
        max-width: 72.5rem;
        width: 100%;
        margin: 0 auto 1.125rem;
        gap: 1rem;
        align-items: center;
        padding-top: 3rem;
    }

    .nav__logo{
        max-width: 7.125rem;
        width: 100%;
    }

    .nav__logo-img{
        width: 100%;
    }

    .nav__right{
        display: flex;
        justify-content: space-between;
        gap: 2rem;
        align-items: center;
    }

    .nav__list{
        display: flex;
        gap: 4rem;
        list-style: none;
    }

    .nav__list-item{
        cursor: pointer;
        font-family: Google Sans;
        font-size: 1.0625rem;
        padding: 0.5rem;
    }

    .nav__list-item:hover{
        background: #aaa;
        color: #35475f;
    }

    .nav__buttons{
        display: flex;
        gap: 2rem;
    }

    .nav__button{
        font-family: Google Sans;
        font-weight: 500;
        font-size: 1.0625rem;
        cursor: pointer;
        padding: 0.5625rem 1.375rem;
        background: none;
        border-radius: 0.3125rem;
        border: none;
    }

    .nav__button--singup{
        border: 1px solid #212832;
    }

    .nav__lang{
        padding: 0.25rem 0.5rem;
        cursor: pointer;
    }
</style>