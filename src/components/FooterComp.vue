<script>
  export default{
    name: 'FooterComp',
  }
</script>

<template>
  <div class="contenitore">
    <div class="container bg-light rounded-4">
      <div class="row">
        <div class="col-lg-7">
          <h2 class="fw-bold text-capitalize">we offer awesome services</h2>
          <span>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptatum cumque sed ipsa nostrum incidunt.</span>
        </div>
        <div class="col-lg-5">
          <div class="input-group mb-3 border rounded-pill p-2">
            <input type="text" class="form-control border-0" placeholder="" aria-label="Example text with button addon" aria-describedby="button-addon1">
            <button class="btn btn-outline-secondary rounded-pill" type="button">Button</button>
          </div>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="row">
        <div class="col-lg-3 logo">
          <img src="../../public/images/white-logo-2.png" alt="logo">
          <span class="d-inline-block">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptatum cumque sed ipsa nostrum incidunt.</span>
        </div>
        <div class="col-lg-3 text-capitalize">
          <h6>Quick Links</h6>
          <ul>
            <li><a href="#">services</a></li>
            <li><a href="#">contact</a></li>
            <li><a href="#">blog</a></li>
          </ul>
        </div>
        <div class="col-lg-3 text-capitalize">
          <h6>Resources</h6>
          <ul class="text-end">
            <li><a href="#">art design</a></li>
            <li><a href="#">computer</a></li>
            <li><a href="#">iT news</a></li>
            <li><a href="#">Networking</a></li>
            <li><a href="#">web security</a></li>
          </ul>
        </div>
        <div class="col-lg-3">
          <h6>Contact Us</h6>
          <ul>
            <li><span class="text-white">Address:</span> Patricia C. Amedee 4401 Waldeck Street Grapevien Nashville, Tx 76051</li>
            <li><span class="text-white">Phone:</span> +99 (0) 1010000 888</li>
            <li><span class="text-white">Email:</span> info@yourdomain.com</li>
          </ul>
        </div>
      </div>
    </div>
    <hr>
    <div class="container">
      <div class="row">
        <div class="col-lg-6 copy">
          <span>&#169; Phlox.All Rights Reserved.</span>
        </div>
        <div class="col-lg-6 social text-end">
          <a href="#"><i class="fa-brands fa-instagram"></i></a>
          <a href="#"><i class="fa-brands fa-linkedin-in"></i></a>
          <a href="#"><i class="fa-brands fa-facebook-f"></i></a>
          <a href="#"><i class="fa-brands fa-twitter"></i></a>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.contenitore{
  background: rgb(6, 22, 67);
}
ul{
  list-style-type: none;
  margin-left: 0;
  padding-left: 0;
}
h6{
  color: white;
}
li a, li, .logo, .copy{
  text-decoration: none;
  color: #8888;
}
.social i{
  margin-left: 30px;
}
.social a{
  text-decoration: none;
  color: white;
}
</style>
