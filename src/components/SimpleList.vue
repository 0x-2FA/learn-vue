<template>
    <div class="list">
        <h1>{{ title }} </h1>
        <ul class="list-items">
            <li>{{ items[0] }}</li>
            <li>{{ items[1] }}</li>
            <li>{{ items[2] }}</li>
        </ul>
    </div>
</template>

<script>
export default {
  data() {
    return {
      title: 'Simple List',
      items: ['Bread', 'Cheese', 'Coffee'],
    };
  },
};
</script>

<style>
.list{
    margin-top: 5em;
}

.list-items{
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-size: 1.2em;
    padding-left: 2em;
}

.list-items li + li{
    margin-top: 1.2em;
}
</style>
