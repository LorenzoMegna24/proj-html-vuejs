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
  <div class="text-center mt-5 col-12">
    <span>Our Services</span>
    <h2><strong>What</strong> We Do</h2>
    <span>When, while the lovley valley teems with vapor around meand the</span>
  </div>
    <div class="carte container text-center">
    <div class="row align-items-center">
      <CardServices v-for="(element, index) in services" :key="index" :card="element"/>
    </div>
  </div>


</template>

<style lang="scss" scoped>
  .carte{
    margin-top: 150px;
  }
</style>
