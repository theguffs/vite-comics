<script>
import AppFooter from './components/Appfooter.vue';
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';

export default {
  data() {
    return {
    }
  },
  components: {
    AppHeader,
    AppMain,
    AppFooter
  },
  methods: {
    IncrementCount(){
      this.count++
    }
  }
}
</script>

<template>
<div>

  <!-- Header component -->
  <AppHeader />

  <!-- Main content component -->
  <AppMain />
  
  <!-- App Footer component -->
  <AppFooter />

</div>
</template>

<style lang="scss" scope>
 
</style>
npm,