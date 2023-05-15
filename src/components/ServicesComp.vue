<script>
  import CardServices from './CardServices.vue';

  export default{
    name: 'ServicesComp',
    components:{
      CardServices
    },
    data(){
      return{
        services: [
            {
                title: 'Data Analysis',
                img: '../../public/images/Group-247.png',
                text: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae at odio, aliquam sit libero ullam velit reiciendis, excepturi mollitia, dolorum beatae.',
            },
            {
                title: 'SEO Optimization',
                img: '../../public/images/Group-567.png',
                text: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae at odio, aliquam sit libero ullam velit reiciendis, excepturi mollitia, dolorum beatae.',
            },
            {
                title: 'Security Data',
                img: '../../public/images/Group-538.png',
                text: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae at odio, aliquam sit libero ullam velit reiciendis, excepturi mollitia, dolorum beatae.',
            },
            {
                title: 'Branding Strategy',
                img: '../../public/images/Group-566.png',
                text: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae at odio, aliquam sit libero ullam velit reiciendis, excepturi mollitia, dolorum beatae.',
            },
        ],

      }
    },
  }
</script>

<template>
  <div id="services" class="text-center container pt-5 pb-5">
    <div class="row justify-content-center">
      <div class="col-lg-6">
        <span>Our Services</span>
        <h2><strong>What</strong> We Do</h2>
        <span>When, while the lovley valley teems with vapor around meand the</span>
      </div>
    </div>
  </div>

  <div class="carte container text-center pt-5">
    <div class="row align-items-center">
      <CardServices v-for="(element, index) in services" :key="index" :card="element"/>
    </div>
  </div>
  <div class="text-center mt-4 pb-4">
    <button type="button" class="btn btn-pink rounded-pill ms-3">View All Services</button>
  </div>

</template>

<style lang="scss" scoped>
</style>
