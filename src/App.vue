<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppBlueNav from './components/AppBlueNav.vue';
import AppFooter from './components/AppFooter.vue';




export default {

  name: 'App',
  data() {
    return {

    }
  },
  components: {
    AppHeader, AppMain, AppBlueNav, AppFooter,

  }

}
</script>

<template>
  <AppHeader></AppHeader>


  <AppMain></AppMain>

  <AppBlueNav></AppBlueNav>
  <AppFooter></AppFooter>
</template>

<style ></style>
