<template>
  <div class="app">
   <div class="container">
    <div class="row m-auto g-0">
      <div class="col-xl-3 col-2 pt-2">
        <sideComp />
      </div>
      <div class="col-xl col borderr pt-2">
        <tweetsComp />
      </div>
      <div class="col-xl-3 col-4 d-lg-block d-none pt-2">
        <newsComp />
      </div>
    </div>
   </div>


  </div>
</template>

<script>
// imports
import sideComp from './components/sideComp.vue'
import tweetsComp from './components/tweetsComp.vue'
import newsComp from './components/newsComp.vue'
export default {
  name: 'App',
  components: {
    sideComp,
    tweetsComp,
    newsComp
  }
}
</script>

<style lang='scss'>
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  text-transform: capitalize;
  font-family: 'Roboto', sans-serif;
  font-style: inherit;
  overflow: hidden;
  color: #fff;
  background: #000;
}
body{
  height: 100vh;
  background: #000 !important;
}
.borderr{
  border: 1px solid rgb(78, 76, 76);
}

</style>
