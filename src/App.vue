<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppBlueNav from './components/AppBlueNav.vue';



export default {

  name: 'App',
  data() {
    return {

    }
  },
  components: {
    AppHeader, AppMain, AppBlueNav,

  }

}
</script>

<template>
  <AppHeader></AppHeader>


  <AppMain></AppMain>

  <AppBlueNav></AppBlueNav>
</template>

<style ></style>
