<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <programme/>
    <brand/>
    <alumni/>
    <tester/>
    <faq/>
    <footerr/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import programme from './components/programme.vue';
import brand from './components/brand.vue';
import alumni from './components/alumni.vue';
import tester from './components/tester.vue';
import faq from './components/faq.vue';
import footerr from './components/footer.vue';
export default {
  name: 'App',
  components: {
    HelloWorld,
    programme,
    brand,
    alumni,
    tester,
    faq,
    footerr
  }
}
</script>

<style>
#app {
 overflow: hidden;
 font-family: 'Rubik', sans-serif;
}
</style>
