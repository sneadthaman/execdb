<template>
  <div class="header">

    <p id="need-help">Need Help?<a href="#" id="chat-btn">Chat</a><a href="#"><font-awesome-icon :icon="faCommentAlt" size="1x" /></a></p>

    <div class="search-box-container">
      <input type="search" id="header-search" placeholder="Search" class="search-box" >
    </div>

    <div class="header-icons">
      <a href="#"><font-awesome-icon :icon="faBell" size="1x"/></a>
      <a href="#"><font-awesome-icon :icon="faEnvelope" size="1x"/></a>
      <a href="#"><font-awesome-icon :icon="faUser" size="1x"/></a>
    </div>
  </div>
</template>

<script>
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome';
import { faBell } from '@fortawesome/free-solid-svg-icons';
import { faEnvelope } from '@fortawesome/free-solid-svg-icons';
import { faUser } from '@fortawesome/free-solid-svg-icons';
import { faCommentAlt } from '@fortawesome/free-solid-svg-icons';

export default{
  name:"header",
  components: {FontAwesomeIcon},
  data(){
    return{
      faBell: faBell,
      faEnvelope: faEnvelope,
      faUser: faUser,
      faCommentAlt: faCommentAlt,
    }
  },
  methods:{
  }
}
</script>

<style scoped>
</style>
