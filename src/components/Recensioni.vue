<script>
  export default{
    name: 'Recensioni',
    props:['recensione']
  }
</script>

<template>
  <div class="col-lg-4 col-md-12">
    <img class="rounded-circle mb-3" :src="recensione.img" alt="">
    <div class="mb-3 position-relative">
      <span class="virgolette position-absolute">&ldquo;</span>
      <i class="fa-solid fa-star"></i>
      <i class="fa-solid fa-star"></i>
      <i class="fa-solid fa-star"></i>
      <i class="fa-regular fa-star"></i>
      <i class="fa-regular fa-star"></i>
    </div>
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
i{
  color: #B6246E;
}
.virgolette{
  color: rgba(187, 187, 187, 0.315);
  font-size: 400px;
  z-index: -1;
  font-weight: bold;
  bottom: -400px;
  left: 25%;
}
</style>