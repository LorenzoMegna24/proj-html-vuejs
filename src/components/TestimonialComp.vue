<script>
  import Recensioni from './Recensioni.vue';
  
  export default{
    name: 'TestimonialComp',
    components:{
      Recensioni,
    },

    data(){
      return{
        recensioni: [
    {
        title: 'Marketing Management',
        img: '../../public/images/szabo-viktor-1266895-unsplash-1024x1024.png',
        name: 'Mickel Angel',
        text: 'Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quod qui modi error saepe alias cum laudantium unde esse, accusantium fugiat odit mollitia.',
    },
    {
        title: 'Marketing Management',
        img: '../../public/images/philipe-cavalcante-539505-unsplash-1024x1024.png',
        name: 'Mickel Angel',
        text: 'Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quod qui modi error saepe alias cum laudantium unde esse, accusantium fugiat odit mollitia.',
    },
    {
        title: 'Marketing Management',
        img: '../../public/images/fabio-spinelli-695744-unsplash-1024x1024.png',
        name: 'Mickel Angel',
        text: 'Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quod qui modi error saepe alias cum laudantium unde esse, accusantium fugiat odit mollitia.',
    },
],
      }
    }
  }
</script>

<template>
    <div class="container">
    <div class="row justify-content-center text-center pt-5 pb-5">
      <div class="col-lg-6">
        <span>Testimonial</span>
        <h2><strong>What</strong> People Say</h2>
        <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi libero fuga totam ducimus quam porro provident officia ipsa dignissimos maxime expedita mollitia.</span>
      </div>
    </div>
  </div>
  <div class="container">
    <div class="row text-center pt-4 pb-5 mb-5">
      <Recensioni v-for="(element, index) in recensioni" :key="index" :recensione="element"/>
    </div>
  </div>
  <div class="container pb-5 mb-5">
    <div class="row pb-5">
      <div class="brand col-lg-12 d-flex justify-content-between">
        <img src="../../public/images/client-1-1.png" alt="">
        <img src="../../public/images/clienty-2.png" alt="">
        <img src="../../public/images/clienty-3.png" alt="">
        <img src="../../public/images/clienty-4.png" alt="">
        <img src="../../public/images/client-5.png" alt="">
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.brand img{
height: 50%;
}
</style>
