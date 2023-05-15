<script>
  export default{
    name: 'CardServices',
    props: ['card'],
    data(){
      return{

      }
    },
  }
</script>

<template>
  <div class="col-lg-3 col-md-6 col-sm-12">
    <div class="card border border-0">
      <img :src="card.img" class="card-img-top" alt="...">
      <div class="card-body">
        <h3 class="card-title">{{ card.title }}</h3>
        <p class="card-text">{{ card.text }}</p>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  img{
    width: 65%;
    margin: auto;
  }
</style>
