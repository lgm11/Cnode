<template>
  <div id="app">
    <Header></Header>
    <div class="main">
      <Postlist></Postlist>
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Postlist from './components/Postlist.vue'
export default {
  components:{
    Header,Postlist
  }
}
</script>

<style lang="scss">
.main{
  width: 80%;
  margin: 0 auto;
}
</style>
