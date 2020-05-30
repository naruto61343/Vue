
<template>
  <div id="app">   
      <div class="col-xs-12">
                <app-user></app-user>
            </div>
    </div>
  
</template>

<script>
 import User from './components/User.vue';

export default {
  name: 'App',
  components: {
    appUser: User
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
