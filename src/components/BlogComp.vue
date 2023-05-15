<script>
  export default{
    name: 'BlogComp',     
    
  }
</script>

<template>
  <div id="blog" class="container mt-5 mb-5">
    <div class="row justify-content-center text-center pt-5">
      <div class="col-lg-6">
        <span class="section-title">Blog</span>
        <h2><strong>Latest</strong> Post</h2>
        <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi libero fuga totam ducimus quam porro provident officia ipsa dignissimos maxime expedita mollitia.</span>
      </div>
    </div>
  </div>
  <div class="container pt-3 mb-5 pb-5">
    <div class="row">
      <div class="col-lg-6 col-md-12">
        <div class="card prima-card rounded-4">
          <div class="card-body rounded-4 opacita d-flex align-items-end text-white">
            <div>
              <span>April 21,2019 . by Paul</span>
              <h5 class="card-title pt-4 pb-3">Amazon gets CCI nod to acquire 49% stake in</h5>
              <div class="d-flex">
                <p class="card-text w-75 pe-1">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                <button type="button" class="btn w-25 h-25 bg-white rounded-pill">Read More</button>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-12">
        <div class="card non-attiva uno rounded-4">
          <div class="card-body rounded-4 text-white d-flex flex-column justify-content-between">
            <span>April 21,2019 . by Paul</span>
            <h5 class="card-title">Clearing Corporations get SEBI nod to invest in overnight funds</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <button type="button" class="btn bg-white w-50 rounded-pill">Read More</button>
          </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-12">
        <div class="card non-attiva due rounded-4">
          <div class="card-body rounded-4 text-white d-flex flex-column justify-content-between">
            <span>April 21,2019 . by Paul</span>
            <h5 class="card-title">Shabnam Dhillion, wife of RSSB chief Guider Dhillion, passes away in London</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <button type="button" class="btn bg-white w-50 rounded-pill">Read More</button>
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
.opacita{
  background-color: rgba(0, 0, 0, 0.614);
}
.prima-card{
  background-image: url(../../public/images/headway-537308-unsplash-1380x703.jpg);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
}
.non-attiva{
  background: rgb(8,28,83);
  background: linear-gradient(325deg, rgba(8,28,83,1) 11%, rgba(0,0,0,1) 100%);
}
.uno:hover{
  background-image: url(../../public/images/studio-republic-644339-unsplash-1380x703.jpg);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
}
.due:hover{
  background-image: url(../../public/images/timon-studler-63413-unsplash-1380x703.jpg);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
}
.card-body:hover{
  background-color: rgba(0, 0, 0, 0.614);

}
.btn:hover{
  box-shadow: 0px 0px 6px 5px rgba(255, 255, 255, 0.30);
  color: black;
}
</style>