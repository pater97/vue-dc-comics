<template>
    <div class="row">
        <div class="serie">
            <img :src="image" alt="">
            <h3>{{titolo}}</h3>
        </div>
    </div>
</template>

<script>
export default {
    props:{
        image:String,
        titolo:String
    }
}
</script>

<style lang="scss">
.row{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    .serie{
        width: calc((100%/12)*2)
    }
}
</style>