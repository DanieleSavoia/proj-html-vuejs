<script>
import headerVue from './components/headerVue.vue'
import firstSection from './components/firstSection.vue'
import secondSection from './components/secondSection.vue'
import thirdSection from './components/thirdSection.vue'
import fourthSection from './components/fourthSection.vue'
import footerVue from './components/footerVue.vue'
import { store } from './store'
export default {
  data() {
    return {
      store,
    };
  },
  components: {
    headerVue,
    firstSection,
    secondSection,
    thirdSection,
    fourthSection,
    footerVue,
  },

}
</script>

<template>
  <main>
    <headerVue/>
    <firstSection/>
    <secondSection/>
    <thirdSection/>
    <fourthSection/>
    <footerVue/>
  </main>
</template>

<style>
body {
  margin: 0;
}
</style>