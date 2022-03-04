<template>
  <div id="app">
    <MyHeader></MyHeader>
    <MyJumbo></MyJumbo>
    <MyCertification></MyCertification>
    <MyServices></MyServices>
    <MyLogistical></MyLogistical>
    <MyFooter></MyFooter>
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MyJumbo from './components/MyJumbo.vue'
import MyCertification from './components/MyCertification.vue'
import MyServices from './components/MyServices.vue'
import MyLogistical from './components/MyLogistical.vue'
import MyFooter from './components/MyFooter.vue'

import "./assets/general.scss";

export default {
  name: 'App',
  components: {
    MyHeader,
    MyJumbo,
    MyCertification,
    MyServices,
    MyLogistical,
    MyFooter,
  }
}
</script>
  

<style lang="scss">

</style>
