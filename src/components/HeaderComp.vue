<script>
  export default{
    name: 'HeaderComp',
  }
</script>

<template>
  <div class="container w-75 text-white">
    <div class="row">
      <div class="col-lg-5 d-flex flex-column justify-content-center">
        <h1>
          <strong>Businness Planning</strong><br> Digital Tecnology<br> <strong>Modern Solution!</strong> 
        </h1>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae at odio, aliquam sit libero ullam velit reiciendis, excepturi mollitia, dolorum beatae.
        </p>
        <div>
          <button type="button" class="btn btn-primary rounded-pill ms-3">Primary</button>
          <button type="button" class="btn btn-primary rounded-pill ms-3">Primary</button>
        </div>
      </div>
      <div class="col-lg-7 d-flex justify-content-end align-items-center">
        <img src="../../public/images/header.png" alt="">
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  img{
    height: 70%;
  }

</style>
