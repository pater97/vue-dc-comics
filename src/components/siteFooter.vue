<template>
    <div class="general_footer">
        <!-- container principale  -->
        <div class="container_footer">
            <!-- contenitore colonne link  -->
            <section class="link">
                <div class="col-2">
                    <h2>
                        DC COMICS
                    </h2>
                        <ul>
                            <li>Charaters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>Tv</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                        </ul>
                    <h2>SHOP</h2>
                        <ul>
                            <li>Shop DC</li>
                            <li>Shop DC collectibles</li>
                        </ul>
                </div>
                <div class="col-2">
                    <h2>
                        DC
                    </h2>
                    <ul>
                        <li>Terms of use</li>
                        <li>Privacy polici(new)</li>
                        <li>Add choices</li>
                        <li>Advertaising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>Talent Workshops</li>
                        <li>Cpsc Certificates</li>
                        <li>Ratings</li>
                        <li>Shop help</li>
                        <li>Contact us</li>
                    </ul>
                </div>
                <div class="col-2">
                    <h2>
                        SITES
                    </h2>
                    <ul>
                        <li>DC</li>
                        <li>Mad megazine</li>
                        <li>DC kids</li>
                        <li>DC universe</li>
                        <li>DC power visa</li>
                    </ul>
                </div>
            </section>
        </div>
            <!-- banner di account  -->
            <section class="account">
                <div class="account_container">
                     <div class="sing_up ">
                    <a href="#">
                        SING-UP NOW!
                    </a>
                </div>
                <div class="follow_us">
                    <div class="follow_text">
                        FOLLOW US
                    </div>
                    <div>
                        <img src="../assets/footer-facebook.png" alt="">
                    </div>
                    <div>
                        <img src="../assets/footer-twitter.png" alt="">
                    </div>
                    <div>
                        <img src="../assets/footer-youtube.png" alt="">
                    </div>
                    <div>
                        <img src="../assets/footer-pinterest.png" alt="">
                    </div>
                    <div>
                        <img src="../assets/footer-periscope.png" alt="">
                    </div>
                </div>
                </div>
               
            </section>
    </div>
</template>

<style lang="scss">
    // importazione variabili 
    @import '/variabili.scss';
    // contenitore generale 
    .general_footer{
        background-image: url(../assets/footer-bg.jpg);
        background-size: cover;
    }
    .container_footer{
        display: flex;
        width: $generalWidth;
        margin: auto;
    }
    .link{
        display: flex;
    }
    .col-2{
        width: calc((100%/12)*4);
        padding: 2rem 2rem 2rem 0rem;
        // TITOLO PARAGRAFO 
        h2{
            padding: 1rem 0;
            font-size: 1rem;
            color: white;
        }
        // lista
        ul{
            list-style: none;
            font-size: .8rem;
            font-weight: 300;
            color: #959595;
            line-height: 1.4rem;
        }
    }
    .account{
        background-color:#303030 ;
        height: 5rem;
            }
        .account_container{
            width: $generalWidth;
            margin: auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            height: 100%;
            // sing-up
            a{
                text-decoration: none;
                color: white;
                padding:.7rem .5rem;
                border: 1px solid $brandColor;
                font-size: .8rem;
            }
            .follow_us{
                display: flex;
                align-items: center;
                // icone
                div{
                    padding-left: 1rem;
                }
                // testo 
                .follow_text{
                    color: $brandColor;
                }
            }
        }
</style>