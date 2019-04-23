<template>
  <div id="app">
    <Header/>
    <Study/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Header from './components/Header.vue';
import Study from './components/Study.vue';

@Component({
  components: {
    Header,
    Study,
  },
})
export default class App extends Vue {}
</script>

<style lang="scss">
  @import '../node_modules/bootstrap/scss/bootstrap.scss';
</style>
