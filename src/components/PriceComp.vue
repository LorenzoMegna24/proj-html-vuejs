<script>
  export default{
    name: 'PriceComp',     
  }
</script>

<template>
  <div class="contenitore">
    <div class="text-center container text-white">
      <div class="row justify-content-center">
        <div class="col-lg-6">
          <span>Price List</span>
          <h3 class="text-capitalize"><strong>our</strong> pricing</h3>
          <span>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quod qui modi error saepe alias cum laudantium unde esse, accusantium fugiat odit mollitia.</span>
        </div>
      </div>
    </div>
    <div class="container text-center w-75">
      <div class="row">
        <div class="col-lg-4">
          <div class="card rounded-4">
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
              <button type="button" class="mt-5 btn btn-danger rounded-pill">Danger</button>
            </div>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="card rounded-4">
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
              <button type="button" class="mt-5 btn btn-danger rounded-pill">Danger</button>
            </div>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="card rounded-4">
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
              <button type="button" class="mt-5 btn btn-danger rounded-pill">Danger</button>
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
</style>