<script>
import AppNavbar from './components/AppNavbar.vue';
import AppContact from './components/AppContact.vue';
import AppMenu from './components/AppMenu.vue';
import AppDc from './components/AppDc.vue';
import AppFooter from './components/AppFooter.vue'

export default {
  data() {
    return {
    }
  },
  components: {
    AppNavbar,
    AppContact,
    AppMenu,
    AppDc,
    AppFooter
  }
}
</script>

  <!-- ////////////////////////////////////////////////////////////// -->

<template>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@300;500;700&family=PT+Sans:wght@400;700&family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">

  <AppNavbar></AppNavbar>

  <AppContact></AppContact>

  <AppMenu></AppMenu>

  <AppDc></AppDc>

  <AppFooter></AppFooter>

</template>


  <!-- ////////////////////////////////////////////////////////////// -->




<style>

</style>
