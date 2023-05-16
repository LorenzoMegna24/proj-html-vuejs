<script>
  export default{
    name: 'PortfolioComp',

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

        attiva: 0,
        slider: null,

      }
    },
    methods:{
      prev(){

        this.attiva--

        if ( this.attiva < 0 ) {
          this.attiva = this.portfolio.length - 1
        }
      },
      next(){

        this.attiva++

        if ( this.attiva > this.portfolio.length - 1 ) {
          this.attiva = 0
        }
      },
      autoSlide(){
        this.slider = setInterval( ()=>{
          this.next()
        }, 2000)
      },

      stopSlide(){
        clearInterval(this.slider)
        this.slider = null
      }
    },
    created(){
      this.autoSlide()
    }
  }
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
  <div class="container">
    <div class="row justify-content-around pb-5 mb-5">
      <!-- <CardPortfolio v-for="(element, index) in portfolio" :key="index" :lavori="element"/> -->
      <div class="col-lg-6 d-flex align-items-center" @mouseover="stopSlide" @mouseleave="autoSlide">
        <div class="prev me-4 rounded-circle p-2 d-flex align-items-center" @click="prev">
          <i class="fa-solid fa-circle-arrow-left fs-2"></i>
        </div>
        <div class="card rounded-4 shadow border-0" >
          <img class="rounded-4" :src="portfolio[attiva].img" alt="">
          <div class="card-body d-flex justify-content-between mb-2 pb-0">
            <h5 class="card-title">{{ portfolio[attiva].title }}</h5>
            <span class="sub">{{ portfolio[attiva].text }}</span>
          </div>
        </div>
        <div class="next ms-4 rounded-circle p-2 d-flex align-items-center" @click="next">
          <i class="fa-solid fa-circle-arrow-right fs-2"></i>
        </div>
      </div>
    </div>
  </div>
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
  .prev, .next{
    background: rgb(249,99,107);
    background: linear-gradient(270deg, rgba(249,99,107,1) 43%, rgba(182,36,110,1) 100%);
    cursor: pointer;
  }
  i{
    color: white;
  }
  i:hover{
    box-shadow: 0px 0px 20px 5px rgba(249,99,107,0.61);
  }
</style>