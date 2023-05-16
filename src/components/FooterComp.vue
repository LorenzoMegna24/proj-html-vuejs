<script>
  export default{
    name: 'FooterComp',
  }
</script>

<template>
  <div class="contenitore position-relative">
    <div class="mail container bg-light rounded-4 position-absolute">
      <div class="row">
        <div class="col-lg-7">
          <h2 class="fw-bold text-capitalize">we offer awesome services</h2>
          <span>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptatum cumque sed ipsa nostrum incidunt.</span>
        </div>
        <div class="col-lg-5 d-flex align-items-center">
          <div class="input-group mb-3 border rounded-pill p-2 bg-white">
            <input type="text" class="form-control border-0" placeholder="" aria-label="Example text with button addon" aria-describedby="button-addon1">
            <button class="btn btn-blue rounded-pill" type="button">Subscribe</button>
          </div>
        </div>
      </div>
    </div>
    <div id="contact" class="container mt-5 p-2">
      <div class="row mt-5 p-5">
        <div class="col-lg-3 col-md-12 logo">
          <img src="../../public/images/white-logo-2.png" alt="logo">
          <span class="d-inline-block mt-3">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptatum cumque sed ipsa nostrum incidunt.</span>
        </div>
        <div class="col-lg-3 col-md-12 text-capitalize ps-5">
          <h6>Quick Links</h6>
          <ul>
            <li><a href="#">services</a></li>
            <li><a href="#">contact</a></li>
            <li><a href="#">blog</a></li>
          </ul>
        </div>
        <div class="col-lg-3 col-md-12 text-capitalize">
          <h6>Resources</h6>
          <ul class="text-end pe-5 me-5">
            <li><a href="#">art design</a></li>
            <li><a href="#">computer</a></li>
            <li><a href="#">iT news</a></li>
            <li><a href="#">Networking</a></li>
            <li><a href="#">web security</a></li>
          </ul>
        </div>
        <div class="col-lg-3 col-sm-12">
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
      <div class="row pb-3">
        <div class="col-lg-6 copy">
          <span>&#169; Phlox.All Rights Reserved.</span>
        </div>
        <div class="col-lg-6 social text-end position-relative">
          <a href="#"><i class="fa-brands fa-instagram"></i></a>
          <a href="#"><i class="fa-brands fa-linkedin-in"></i></a>
          <a href="#"><i class="fa-brands fa-facebook-f"></i></a>
          <a href="#"><i class="fa-brands fa-twitter"></i></a>
          <div class="btn-up position-absolute rounded-circle d-flex align-items-center justify-content-center">
            <a href="#nav" ><i class="fa-solid fa-arrow-up"></i></a>
          </div>
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
li a{
  text-decoration: none;
}
li a:hover{
  color: white;
}

li a, li, .logo, .copy, hr{
  color: #888888;
}
.social i{
  margin-left: 30px;
}
.social a{
  text-decoration: none;
  color: white;
}
.mail{
padding: 50px;
top: -30%;
left: 8%;
background: rgb(249,99,107);
background: linear-gradient(315deg, rgba(249,99,107,1) 43%, rgba(182,36,110,1) 100%);
color: white;

}
.btn-up{
  display: inline-block;
  top: -30px;
  right: -45px;
  text-align: center;
  color: white;
  background: rgb(249,99,107);
  background: linear-gradient(270deg, rgba(249,99,107,1) 43%, rgba(182,36,110,1) 100%);
  width: 36px;
  height: 36px;

}

.btn-up:hover{
  box-shadow: 0px 0px 20px 5px rgba(249,99,107,0.61);
  transform: scale(1.1);
}

.btn-up i{
  margin: 0;
  font-size: 20px;
}

</style>
