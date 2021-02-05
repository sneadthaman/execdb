<template>
  <div id="app">
    <navigation></navigation>
    <top-header></top-header>
    <tile-container></tile-container>
    
  </div>
</template>

<script>
import Navigation from "@/components/Navigation.vue";
import Header from "@/components/Header.vue";
import TileContainer from '@/components/TileContainer.vue';

export default {
  name: 'App',
  components: {
    'navigation': Navigation,
    'top-header': Header,
    'tile-container': TileContainer,
  }
}
</script>

<style lang="scss">
@import "./assets/scss/style.scss"
</style>
