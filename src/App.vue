<template>
  <div>
    <router-view></router-view>
    <FooterGuide v-show="$route.meta.showFooter"></FooterGuide>
  </div>
</template>

<script>
    import FooterGuide from "./component/FooterGuide/FooterGuide";
    export default {
       components:{
          FooterGuide
       }
    }
</script>

<style lang="stylus" rel="stylesheet/stylus">
  .app
    color:red;
</style>
