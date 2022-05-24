<template>
  <div>
      <navbar class="sticky top-0 bg-white z-50"/>
      <home/>
      <services/>
      <projects/>
      <whyUs/>
      <ourClint/>
      <contuctUs/>
      <footerbd/>
  </div>
</template>

<script>
import navbar from '../components/navbar.vue'
import home from './hero.vue'
import services from './services.vue'
import projects from './projects.vue'
import whyUs from './whyUs.vue'
import contuctUs from './contuctUs.vue'
import footerbd from '../components/footer.vue'
import ourClint from './our_clint.vue'

export default {
  components:{
    navbar,home,services, projects, whyUs,contuctUs,ourClint,
    footerbd
  }
}
</script>
