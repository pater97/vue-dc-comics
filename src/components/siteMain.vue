<template>
    <div>
        <section>
            <!-- banner nero  -->
            <div class="black_ban">
                <div class="container">
                -->content goes here
                </div>
            </div>
            <!-- banner blue  -->
            <div class="blue_ban">
                <blueBan/>
            </div>
        </section>
    </div>
</template>

<script>
// importare ban blu 
import blueBan from './blueBan.vue'
export default {
    components: {
        blueBan
    }
}
</script>

<style lang="scss">
// importazione variabili 
@import '/variabili.scss';
// contenitore nero 
.container{
    width: $generalWidth;
    color: white;
    font-weight: 700;
    font-size: 1.5rem
};
 .black_ban{
    background-color: black;
    width: 100%;
     }
    
</style>