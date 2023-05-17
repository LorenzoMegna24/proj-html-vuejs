<script>
  import { defineComponent } from 'vue'
  import { Carousel, Navigation, Slide } from 'vue3-carousel'

  import 'vue3-carousel/dist/carousel.css'

  export default defineComponent({
    name: 'WrapAround',
    components: {
      Carousel,
      Slide,
      Navigation,
    },
    data(){
      return{
        portfolio: [
            {
                title: 'Basket of Flower on table',
                img: '../../public/images/8wa60okr-1-790x576.jpg',
                text: 'Branding Strategy',
            },
            {
                title: 'Purinky Products',
                img: '../../public/images/DRY-1-790x576.jpg',
                text: 'Digital Experience',
            },
            {
                title: 'Satisfy Poster',
                img: '../../public/images/a247b00b-3621-470f-b4b8-b3ac46f25907-1-790x576.jpg',
                text: 'Branding Strategy',
            },
            {
                title: 'Mock-up App',
                img: '../../public/images/84316050-0af0-49db-a53a-241d47ddad0e-2-790x576.jpg',
                text: 'Digital Experience',
            },
        ],

      }
    },
  })
</script>

<template>
  <div id="portfolio" class="container mb-5 mt-5">
  <div class="row">
    <div class="col-lg-12">
      <span class="section-title">Portfolio</span>
      <h3><strong>latest</strong> work</h3>
    </div>
  </div>
</div>
<Carousel :items-to-show="2.5" :wrap-around="true">
  <div class="container"></div>
  <Slide v-for="(element,index) in portfolio" :key="index">
    <div class="card mb-5 w-75 rounded-4 shadow border-0" >
        <img class="rounded-4" :src="element.img" alt="">
        <div class="card-body d-flex justify-content-between mb-2 pb-0">
          <h5 class="card-title">{{ element.title }}</h5>
          <span class="sub">{{ element.text }}</span>
        </div>
      </div>
  </Slide>

  <template #addons>
    <Navigation />
  </template>
</Carousel>
</template>


<style lang="scss" scoped>
  sub{
    font-size: 12px;
  }
  .card:hover{
    background: rgb(249,99,107);
    background: linear-gradient(270deg, rgba(249,99,107,1) 43%, rgba(182,36,110,1) 100%);
    color: white;
  }

  i:hover{
    box-shadow: 0px 0px 20px 5px rgba(249,99,107,0.61);
  }

</style>