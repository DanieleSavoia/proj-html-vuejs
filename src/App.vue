<script>
import headerVue from './components/headerVue.vue'
import firstSection from './components/firstSection.vue'
import secondSection from './components/secondSection.vue'
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
    footerVue,
  },

}
</script>

<template>
  <main>
    <headerVue/>
    <firstSection/>
    <secondSection/>
    <footerVue/>
  </main>
</template>

<style>
</style>