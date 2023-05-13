<script>
  export default{
    name:'NavComp',
  }

</script>

<template>
  <nav class="bg-transparent d-flex justify-content-center">
    <div class="d-flex justify-content-between align-items-center w-75 mt-3">
      <div>
        <a href="#"><img src="../../public/images/white-logo-2.png" alt=""></a>
      </div>
        <ul class="d-flex align-items-center mx-4">
          <li>
            <a href="#">Home</a>
          </li>
          <li>
            <a href="#">Home</a>
          </li>
          <li>
            <a href="#">Home</a>
          </li>
          <li>
            <a href="#">Home</a>
          </li>
          <li>
            <a href="#">Home</a>
          </li>
          <li>
            <a href="#">Home</a>
          </li>
          <li>
            <button type="button" class="ms-4 btn btn-danger rounded-pill">Danger</button>
          </li>
        </ul>
    </div>
  </nav>
</template>

<style lang="scss" scoped>
  ul li{
    list-style-type: none;
    margin-left: 12px;
    margin-top: 11px;
  }
  a{
    text-decoration: none;
    color: white;
  }
</style>
