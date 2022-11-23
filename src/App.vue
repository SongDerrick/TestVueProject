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
    <DemoDrink1 msg1="데자와" msg2="솔의 눈" msg3="베지밀" msg4="두유 검은콩"></DemoDrink1>
    <DemoDrink2 msg1="레드불" msg2="몬스터 에너지" msg3="몬스터 울트라" msg4="핫식스"></DemoDrink2>
  </div>
</template>

<script>
import DemoDrink1 from './components/DemoDrink1.vue'
import DemoDrink2 from './components/DemoDrink2.vue'

export default {
  name: 'App',
  components : {
    DemoDrink1,
    DemoDrink2
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
