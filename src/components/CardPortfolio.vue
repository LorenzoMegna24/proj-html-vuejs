<script>
  export default{
    name: 'PortfolioComp',     
    props:['lavori']
  }
</script>

<template>
  <div class="card rounded-4" style="width: 18rem;">
    <img class="rounded-4" :src="lavori.img" alt="">
    <div class="card-body d-flex mb-0 pb-0">
      <h5 class="card-title">{{ lavori.title }}</h5>
      <span class="card-text">{{ lavori.text }}</span>
    </div>
  </div>
</template>

<style lang="scss" scoped>

</style>