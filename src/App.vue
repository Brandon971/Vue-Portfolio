<template>
  <navBar></navBar>
  <router-view></router-view>
  <Footer></Footer>

</template>
<script>
import navBar from '@/components/Navbar.vue'
import Footer from '@/components/Footer.vue'

export default {
  components: {
    navBar,
    Footer
  }
}
</script>

<style>

</style>
