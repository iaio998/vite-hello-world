<template>

  <AppTitle class="title"/>
 <div class="hero">
  <AppHero/>
 </div>

</template>

<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";
export default {
  components:{
    AppTitle,
    AppHero,
  },
  data (){
    return {

    }
  },
  methods:{},
}
</script>

<style lang="css">
  .title {
    margin-top: 100px;
    text-align:center;
    margin-bottom: 5px;
  };
/* .hero {
  display: flex;
 justify-content: center;
}; */
</style>
