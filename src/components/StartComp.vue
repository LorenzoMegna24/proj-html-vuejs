<script>
export default{
  name: 'StartComp',
}
</script>

<template>
  <div class="contenitore text-white">
    <div class=" container w-75 mt-5 py-5">
      <div class="row align-items-center">
        <div class="col-lg-7 pt-5 pb-5">
          <img src="../../public/images/men-data.png" alt="">
        </div>
        <div class="col-lg-5 pt-5 pb-5">
          <span>Start Your Project</span>
          <h2 class="text-capitalize"><strong>grow your business</strong><br>with our strategy</h2>
          <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Odit adipisci voluptas accusantium, ratione saepe rerum sunt. Neque itaque amet eum consequatur.</p>
          <button type="button" class="btn btn-primary rounded-pill ms-3">Primary</button>
          <button type="button" class="btn btn-primary rounded-pill ms-3">Primary</button>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  img{
    width: 65%;
  }
  .contenitore{
    background: rgb(8,28,83);
    background: linear-gradient(180deg, rgba(8,28,83,1) 11%, rgba(0,0,0,1) 100%);

  }
</style>