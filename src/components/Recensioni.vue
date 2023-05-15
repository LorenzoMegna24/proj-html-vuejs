<script>
  export default{
    name: 'Recensioni',
    props:['recensione']
  }
</script>

<template>
  <div class="col lg-4">
    <img class="rounded-circle" :src="recensione.img" alt="">
    <p>stelle</p>
    <p>{{ recensione.text }}</p>
    <h6>{{ recensione.name }}</h6>
    <span>{{ recensione.title }}</span>
  </div>
</template>

<style lang="scss" scoped>
img{
  width: 20%;
  border: 4px solid #B6246E;
}
</style>