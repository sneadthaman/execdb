<template>
  <div class="tile-container">
    <tile></tile>
    <tile></tile>
    <tile></tile>
    <tile></tile>
  </div>
</template>

<script>
import Tile from './Tile.vue'

export default{
  components: { Tile },
  name:"tile-container",
  data(){
    return{}
  },
  methods:{
  }
}
</script>

<style scoped>
</style>
