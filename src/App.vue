<template>
<div id="navBar">
  <navBar/>
  <Main/>
</div>
</template>

<script>
import navBar from './components/navbar.vue'
import Main from './components/Main.vue'


export default {
  components: {
    navBar,Main
  },
};
</script>

<style>
* {
  box-sizing: border-box;
}

#app {
  /* width: 300px; */
  /* padding: 40px; */
  background-color: rgb(233, 245, 241);  
  border: 30px solid rgb(185, 235, 209);
}
</style>

