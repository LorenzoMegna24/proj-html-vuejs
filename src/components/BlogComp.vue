<script>
  export default{
    name: 'BlogComp',     
    
  }
</script>

<template>
  <div class="container">
    <div class="row justify-content-center text-center pt-5">
      <div class="col-lg-6">
        <span>Blog</span>
        <h2><strong>Latest</strong> Post</h2>
        <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi libero fuga totam ducimus quam porro provident officia ipsa dignissimos maxime expedita mollitia.</span>
      </div>
    </div>
  </div>
  <div class="container">
    <div class="row">
      <div class="col-lg-6">
        <div class="card prima-card rounded-4">
          <div class="card-body d-flex align-items-end text-white">
            <div>
              <h5 class="card-title">Card title</h5>
              <h6 class="card-subtitle mb-2">Card subtitle</h6>
              <div class="d-flex">
                <p class="card-text w-75">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                <button type="button" class="btn btn-danger rounded-pill">Danger</button>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-lg-3">
        <div class="card non-attiva rounded-4">
          <div class="card-body text-white d-flex flex-column justify-content-between">
            <span>April 21,2019 . by Paul</span>
            <h5 class="card-title">Card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <button type="button" class=" w-50 btn btn-danger rounded-pill">Danger</button>
          </div>
        </div>
      </div>
      <div class="col-lg-3">
        <div class="card non-attiva rounded-4">
          <div class="card-body text-white d-flex flex-column justify-content-between">
            <span>April 21,2019 . by Paul</span>
            <h5 class="card-title">Card title</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <button type="button" class=" w-50 btn btn-danger rounded-pill">Danger</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.card{
  height: 400px;
}
.prima-card{
  background-image: url(../../public/images/headway-537308-unsplash-1380x703.jpg);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  filter: brightness(80%);
}
.non-attiva{
  background: rgb(8,28,83);
  background: linear-gradient(325deg, rgba(8,28,83,1) 11%, rgba(0,0,0,1) 100%);
}
</style>