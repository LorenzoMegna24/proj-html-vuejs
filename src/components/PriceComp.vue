<script>
  export default{
    name: 'PriceComp',     
  }
</script>

<template>
  <div class="contenitore">
    <div class="text-center container text-white pt-5 ">
      <div class="row justify-content-center mb-5">
        <div class="col-lg-6">
          <span class="section-title">Price List</span>
          <h3 class="text-capitalize"><strong>our</strong> pricing</h3>
          <span>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quod qui modi error saepe alias cum laudantium unde esse, accusantium fugiat odit mollitia.</span>
        </div>
      </div>
    </div>
    <div class="container text-center">
      <div class="row mb-5 pb-5">
        <div class="col-lg-4 col-md-12 col-sm-12">
          <div class="card border-0 shadow rounded-4">
            <h2 class="bg-text position-absolute">40</h2>
            <div class="card-body">
              <h4 class="card-title">Designing</h4>
              <span class="type">PROCESS</span>
              <h3 class="card-subtitle mb-2">40</h3>
              <span class="sub">Per Month</span>
              <ul>
                <li><strong>Creative</strong> Design Enabled</li>
                <li><strong>Vibrant</strong> Color Usage</li>
                <li><strong>Eye</strong> Catching Design</li>
                <li><strong>Extreme</strong> Typography</li>
                <li><strong>Exceptional</strong> Design</li>
              </ul>
              <button type="button" class="mt-3 mb-3 btn btn-pink rounded-pill">Order Now <i class="fa-solid fa-arrow-right-long"></i></button>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-12 col-sm-12">
          <div class="card card-centrale border-0 shadow rounded-4">
            <h2 class="bg-text position-absolute">60</h2>
            <div class="card-body">
              <h4 class="card-title">Developing</h4>
              <span class="type">PRODUCT</span>
              <h3 class="card-subtitle mb-2">60</h3>
              <span class="sub">Per Month</span>
              <ul>
                <li><strong>Creative</strong> Design Enabled</li>
                <li><strong>Vibrant</strong> Color Usage</li>
                <li><strong>Eye</strong> Catching Design</li>
                <li><strong>Extreme</strong> Typography</li>
                <li><strong>Exceptional</strong> Design</li>
              </ul>
              <button type="button" class="mt-3 mb-3 btn bg-white  rounded-pill">Order Now <i class="fa-solid fa-arrow-right-long"></i></button>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-md-12 col-sm-12">
          <div class="card border-0 shadow rounded-4">
            <h2 class="bg-text position-absolute">80</h2>
            <div class="card-body">
              <h4 class="card-title">Supporting</h4>
              <span class="type">CLIENTS</span>
              <h3 class="card-subtitle mb-2">80</h3>
              <span class="sub">Per Month</span>
              <ul>
                <li><strong>Creative</strong> Design Enabled</li>
                <li><strong>Vibrant</strong> Color Usage</li>
                <li><strong>Eye</strong> Catching Design</li>
                <li><strong>Extreme</strong> Typography</li>
                <li><strong>Exceptional</strong> Design</li>
              </ul>
              <button type="button" class="mt-3 mb-3 btn btn-pink rounded-pill">Order Now <i class="fa-solid fa-arrow-right-long"></i></button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

</template>

<style lang="scss" scoped>
  ul{
    list-style-type: none;
    margin-top: 40px;
  }
  li{
    margin-top: 15px;
    font-size: 15px;
  }
  .card h3{
    font-size: 80px;
    margin-top: 60px;

  }
  .card h4{
    font-size: 40px;
  }
  .type{
    font-weight: bold;
    font-size: 14px;
  }
  .sub{
    font-size: 12px;
  }
  .contenitore{
    background: rgb(8,28,83);
    background: linear-gradient(180deg, rgba(8,28,83,1) 11%, rgba(0,0,0,1) 65%, rgba(255,255,255,1) 65%);
  }
  .card-centrale{
    background: rgb(249,99,107);
    background: linear-gradient(315deg, rgba(249,99,107,1) 43%, rgba(182,36,110,1) 100%);
    color: white;
  }
  .card-centrale button{
    color: #f9636b;
  }

  .card-body{
    z-index: 2;
  }
  .card-centrale button:hover{
    box-shadow: 0px 0px 10px 5px rgba(255, 255, 255, 0.30);
  }

  .bg-text{
    right: -11px;
    top: -90px;
    z-index: 0;
    font-size: 300px;
    color: rgba(231, 231, 231, 0.521);

  }
</style>