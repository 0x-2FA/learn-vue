<template>
  <div>
      <h1>{{ title.toLowerCase() }}</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: 'First Component Yay!!!',
    };
  },
};
</script>

<style>
h1{
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  text-align: center;
  color: rgb(0, 126, 59);
  margin-top: 3em;
}
</style>
