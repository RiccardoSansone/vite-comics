<script>
import AppNavbar from './components/AppNavbar.vue';
import AppContact from './components/AppContact.vue';
import AppMenu from './components/AppMenu.vue';
import AppDc from './components/AppDc.vue'

export default {
  data() {
    return {
    }
  },
  components: {
    AppNavbar,
    AppContact,
    AppMenu,
    AppDc
  }
}
</script>

  <!-- ////////////////////////////////////////////////////////////// -->

<template>

  <AppNavbar></AppNavbar>

  <AppContact></AppContact>

  <AppMenu></AppMenu>

  <AppDc></AppDc>

</template>


  <!-- ////////////////////////////////////////////////////////////// -->




<style>

</style>
