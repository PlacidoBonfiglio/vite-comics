<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
import AppBonus from './components/AppBonus.vue';

export default {
  data() {
    return {

    }
  },
  components: {
    AppHeader,
    AppMain,
    AppBonus,
    AppFooter
  }
}

</script>

<template>
  <AppHeader/>
  <AppMain/>
  <AppBonus/>
  <AppFooter/>
</template>

<style lang="scss">
@use "styles/general.scss" as *;
</style>
