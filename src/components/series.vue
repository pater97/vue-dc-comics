<template>
  <div class="oggetto_singolo">
    <img class="cover" :src="image" alt="" />
    <h3>{{ titolo }}</h3>
  </div>
</template>

<script>
export default {
  props: {
    image: String,
    titolo: String,
  },
};
</script>

<style lang="scss">
    .oggetto_singolo{
        padding: 1rem;
        h3{
          padding: .5rem 0;
          font-weight: 300;
          font-size: .9rem;
        }
    }
    .cover{
        height: 11rem;
        width: 100%;
        object-fit: cover;
        object-position: top;
    }
    
</style>