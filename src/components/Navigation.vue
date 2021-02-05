<template>
  <div class="navigation">
    <div class="vertical-flex-container">
      <div id="logo">
        <a href="#"><img src="../assets/images/janvey_logo-125.png" ></a>
      </div>
      <div id="menu">
        <div class="menu-items" id="main-menu">
          <!-- Main Menu Nav Items -->
          <p class="menu-header">Main Menu</p>
          <ul>
            <li><a href="#">Dashboard</a></li>
            <li><a href="#">Sales</a></li>
            <li><a href="#">Marketing</a></li>
            <li><a href="#">Operations</a></li>
            <li><a href="#">Finance</a></li>
          </ul>
        </div>
        <div class="menu-items" id="settings-menu">
          <!-- Settings Menu Items -->
          <p class="menu-header">Settings</p>
          <ul>
            <li><a href="#">User Settings</a></li>
            <li><a href="#">Admin</a></li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default{
  name:"navigation",
  data(){
    return{}
  },
  methods:{
  }
}
</script>

<style scoped>
</style>
