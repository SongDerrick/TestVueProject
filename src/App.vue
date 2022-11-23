<template>
  <!-- <div id="app">
    <md-card class="md-with-hover">
      <md-card-header>
        <div class="md-title">
          DEMO
        </div>
      </md-card-header>
    </md-card>
  </div> -->
  <div id="app">
    <DemoDrink></DemoDrink>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import DemoDrink from './components/DemoDrink.vue'

export default {
  name: 'App',
  components : {
    DemoDrink
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
