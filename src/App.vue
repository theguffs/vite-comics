<script>
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
  <MainApp />
  
</div>
</template>

<style lang="scss" scope>
 
</style>
npm,