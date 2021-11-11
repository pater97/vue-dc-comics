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
            <!-- banner di account  -->
            <section class="account">

            </section>
        </div>
    </div>
</template>

<style lang="scss">
    // importazione variabili 
    @import '/variabili.scss';
    // contenitore generale 
    .general_footer{
        background-image: url(../assets/footer-bg.jpg);
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
        }
    }
</style>