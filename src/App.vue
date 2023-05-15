<script>
  import NavComp from './components/NavComp.vue';
  import HeaderComp from './components/HeaderComp.vue';
  import ServicesComp from './components/ServicesComp.vue';
  import StartComp from './components/StartComp.vue';
  import PortfolioComp from './components/PortfolioComp.vue';
  import PriceComp from './components/PriceComp.vue';
  import BlogComp from './components/BlogComp.vue';
  import TestimonialComp from './components/TestimonialComp.vue';
  import FooterComp from './components/FooterComp.vue';



  export default{
    name: 'App',
    components:{
      NavComp,
      HeaderComp,
      ServicesComp,
      StartComp,
      PortfolioComp,
      PriceComp,
      BlogComp,
      TestimonialComp,
      FooterComp,
    }
  }
</script>

<template>
  <header>
    <NavComp/>
    <HeaderComp/>
  </header>
  <main>
    <ServicesComp/>
    <StartComp/>
    <PortfolioComp/>
    <PriceComp/>
    <BlogComp/>
    <TestimonialComp/>
  </main>
  <footer>
    <FooterComp/>
  </footer>
</template>

<style lang="scss">
@use './style/main.scss';
header{
  background: rgb(8,28,83);
  background: linear-gradient(180deg, rgba(8,28,83,1) 11%, rgba(0,0,0,1) 100%);
}
</style>
