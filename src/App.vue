<script>
  import NavComp from './components/NavComp.vue';
  import HeaderComp from './components/HeaderComp.vue';

  export default{
    name: 'App',
    components:{
      NavComp,
      HeaderComp,
    }
  }
</script>

<template>
  <header>
    <NavComp/>
    <HeaderComp/>
  </header>
</template>

<style lang="scss">
@use './style/main.scss';
header{
  background: rgb(8,28,83);
  background: linear-gradient(180deg, rgba(8,28,83,1) 11%, rgba(0,0,0,1) 100%);
}
</style>
