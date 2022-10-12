<template>
  <div id="app">
  <Calc/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Calc  from './components/Calc.vue'

@Component({
  components: {
    Calc
  },
})
export default class App extends Vue {}
</script>

<style lang="scss">

</style>
