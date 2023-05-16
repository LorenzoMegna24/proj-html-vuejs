<script>
  export default{
    name:'NavComp',
  }

</script>

<template>
  <div id="nav" class="container">
    <div class="row pt-4">
      <div class="col-lg-6 col-md-4">
        <a href="#"><img src="../../public/images/white-logo-2.png" alt=""></a>
      </div>
      <div class="col-lg-6 col-md-4">
        <ul class="d-flex align-items-center mx-4">
          <li>
            <a href="#">Home</a>
          </li>
          <li>
            <a href="#start">Start</a>
          </li>
          <li>
            <a href="#services">Services</a>
          </li>
          <li>
            <a href="#blog">Blog</a>
          </li>
          <li>
            <a href="#contact">Contact</a>
          </li>
          <li>
            <a href="#portfolio">Portfolio</a>
          </li>
          <li>
            <button type="button" class="ms-4 btn btn-blue rounded-pill">Sing In</button>
          </li>
        </ul>
      </div>
    </div>
  </div>

</template>

<style lang="scss" scoped>
  ul li{
    list-style-type: none;
    margin-left: 25px;
    margin-top: 11px;
  }
  a{
    text-decoration: none;
    color: white;
  }
  a:hover{
    color: #f9636b;
  }
</style>
