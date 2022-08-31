<template>
  <PageHead />
  <PageLanguages />
  
</template>

<script>
import PageHead from './components/PageHead.vue'
import PageLanguages from './components/PageLanguages.vue'

export default {
  name: 'App',
  components: {
    PageHead,
    PageLanguages
  }
}
</script>

<style>
#app {
  text-align: center;
  color: #2c3e50;
  background: #252525;
}
</style>
