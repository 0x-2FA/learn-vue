<template>
  <div class="first-comp">
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
.first-comp h1{
  text-align: center;
  color: rgb(0, 126, 59);
  margin-top: 3em;
}
</style>
