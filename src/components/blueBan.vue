<template>
    <div class="general_blue">
        <section class="container_blue">
            <div href="#">
                <img src="../assets/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMICS</span>
            </div>
            <div href="#">
                <img src="../assets/buy-comics-merchandise.png" alt="">
                <span>DC MERCHANDISE</span>
            </div>
            <div href="#">
                <img src="../assets/buy-comics-subscriptions.png" alt="">
                <span>SUBSCRIPTION</span>
            </div>
            <div href="#">
                <img src="../assets/buy-comics-shop-locator.png" alt="">
                <span>COMIC SHOP LOCATORS</span>
            </div>
            <div href="#">
                <img src="../assets/buy-dc-power-visa.svg" alt="">
                <span>DC POWER VISA</span>
            </div>
        </section>
    </div>
</template>

<style lang="scss">
// importazione variabili
    @import '/variabili.scss';
    // contenitore principale
    .general_blue{
        background-color: $brandColor;
        // contenitore
        .container_blue{
            width: $generalWidth;
            height: 8rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin: auto;
            padding: 0 1.5rem;
            // oggetti link 
            div{
                color: white;
                display: flex;
                align-items: center;
                font-size: .8rem;
                // regolazione grandezza immagini 
                img{
                    width: 3rem;
                }
                span{
                    margin-left: 10px;
                }
            }
        }
    }
</style>