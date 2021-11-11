<template>
    <div>
        <section class="container">
            <div class="logo">
                <img src="../assets/dc-logo.png" alt="">
            </div>
            <nav class="nav_choise">
                <a href="#">CHARATERS</a>
                <a href="#">COMICS</a>
                <a href="#">MOVIES</a>
                <a href="#">TV</a>
                <a href="#">GAMES</a>
                <a href="#">COLLECTIBLES</a>
                <a href="#">VIDEOS</a>
                <a href="#">FANS</a>
                <a href="#">NEWS</a>
                <a href="#">SHOP</a>
            </nav>
        </section>
    </div>
</template>

<style lang="scss">
        @import '/variabili.scss';
    .container{
        width: $generalWidth; 
        margin: auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 2rem;
        img{
            width: 5rem;
        }
        a{
            text-decoration: none;
            color: black;
            padding: 1rem;
            font-weight: 700;
            &:hover{
                color: $brandColor;
                border-bottom: 3px solid $brandColor;
            }
        }
    }
</style>