<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  components: {
  },
  created () {
  },
  methods: {
  }
}
</script>

<style lang="scss">
@import './assets/common';
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.header {
  .rightBtn {
    font-size: 1.5rem;
    font-weight: 100;
    color: #fff;
  }
}
</style>
