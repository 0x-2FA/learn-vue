<template>
  <div>
    <FirstComp />
    <SimpleButton />
  </div>
</template>

<script>
import FirstComp from './components/FirstComp';
import SimpleButton from './components/SimpleButton';

export default {
  components: {
    FirstComp,
    SimpleButton,
  },
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
