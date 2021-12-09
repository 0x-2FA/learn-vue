<template>
  <div>
    <FirstComp />
    <SimpleButton />
    <SimpleList />
  </div>
</template>

<script>
import FirstComp from './components/FirstComp';
import SimpleButton from './components/SimpleButton';
import SimpleList from './components/SimpleList';

export default {
  components: {
    FirstComp,
    SimpleButton,
    SimpleList,
  },
};
</script>

<style>

</style>
