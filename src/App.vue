<script>
import AppHeader from './components/AppHeader.vue';

export default {
  data() {
    return {
      count: 0
    }
  },
  components: {
    AppHeader
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

  <AppHeader/>

  <button @click="IncrementCount()">

  </button>
  
</div>
</template>

<style lang="scss" scope>
 
</style>
npm,