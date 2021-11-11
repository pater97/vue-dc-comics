<template>
    <div>
        <!-- container principale -->
        <section class="container">
            <!-- contenitore logo -->
            <div class="logo">
                <img src="../assets/dc-logo.png" alt="">
            </div>
            <!-- contenitore oggetti di navigazione  -->
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
        padding:1rem;
        // dimensione imgg 
        img{
            width: 4rem;
        }
        // modifca oggetti di selezione 
        a{
            text-decoration: none;
            color: black;
            padding:2.3rem 1rem;
            font-weight: 700;
            font-size: .8rem;
            // effettistica oggetti 
            &:hover{
                color: $brandColor;
                border-bottom: 5px solid $brandColor;
            }
        }
    }
</style>