<script>
  import CardPortfolio from './CardPortfolio.vue';
  export default{
    name: 'PortfolioComp',
    components:{
      CardPortfolio,
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
  }
</script>

<template>
  <div class="container w-75 mb-5 mt-5">
    <div class="row">
      <div class="col-lg-12">
        <span>Portfolio</span>
        <h3><strong>latest</strong> work</h3>
      </div>
    </div>
  </div>
  <div>
    <div class="d-flex justify-content-around mb-5">
      <CardPortfolio v-for="(element, index) in portfolio" :key="index" :lavori="element"/>
    </div>
  </div>
</template>

<style lang="scss" scoped>

</style>