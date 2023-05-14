<script>
  export default{
    name: 'PortfolioComp',     
    props:['lavori']
  }
</script>

<template>
  <div class="card rounded-4">
    <img class="rounded-4" :src="lavori.img" alt="">
    <div class="card-body d-flex justify-content-between mb-0 pb-0">
      <h5 class="card-title">{{ lavori.title }}</h5>
      <span>{{ lavori.text }}</span>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  span{
    font-size: 12px;
  }
  .card{
    width: 350px;
  }
</style>