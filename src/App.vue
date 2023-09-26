<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppBlueNav from './components/AppBlueNav.vue';
import AppFooter from './components/AppFooter.vue';
import AppSignUp from './components/AppSignUp.vue';
import AppBanner from './components/AppBanner.vue';








export default {

  name: 'App',
  data() {
    return {

    }
  },
  components: {
    AppHeader, AppMain, AppBlueNav, AppFooter, AppSignUp, AppBanner,

  }

}
</script>

<template>
  <AppHeader></AppHeader>
  <AppBanner></AppBanner>
  <AppMain></AppMain>
  <AppBlueNav></AppBlueNav>
  <AppFooter></AppFooter>
  <AppSignUp></AppSignUp>
</template>

<style >
* {
  font-family: 'Fira Sans', sans-serif;
}
</style>
