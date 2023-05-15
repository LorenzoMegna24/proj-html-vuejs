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
    <div class="card rounded-4 border border-0">
      <img :src="card.img" class="card-img-top rounded-4 position-absolute shadow" alt="...">
      <div class="card-body rounded-4 pt-5 mt-5 shadow">
        <h3 class="card-title">{{ card.title }}</h3>
        <p class="card-text">{{ card.text }}</p>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  img{
    width: 130px;
    margin: auto;
    aspect-ratio: 1;
    top: -25%;
    left: 25%;
    background-color: white;

  }
  .card:hover{
    background: rgb(8,28,83);
    background: linear-gradient(180deg, rgba(8,28,83,1) 11%, rgba(0,0,0,1) 100%);
    color: white;
  }
  .card:hover img{
    background-color: white;
  }
</style>
