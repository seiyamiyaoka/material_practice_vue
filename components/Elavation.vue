<template>
  <div class="elevation-demo">
    <md-content class="md-elevation-1">1</md-content>
    <md-content class="md-elevation-2">2</md-content>
    <md-content class="md-elevation-3">3</md-content>
    <md-content class="md-elevation-4">4</md-content>
    <md-content class="md-elevation-5">5</md-content>
    <md-content class="md-elevation-6">6</md-content>
    <md-content class="md-elevation-7">7</md-content>
    <md-content class="md-elevation-8">8</md-content>
    <md-content class="md-elevation-9">9</md-content>
    <md-content v-for="i in 4" :class= `md-elevation-${i}` :key=i>{{ i }}</md-content>
  </div>
</template>

<script>
  export default {
    name: 'Elevation',
    props: ['dataSize']
  }
</script>

<style lang="scss" scoped>
  .elevation-demo {
    padding: 16px;
    display: flex;
    flex-wrap: wrap;
  }

  .md-content {
    width: 300px;
    height: 300px;
    margin: 12px;
    display: flex;
    align-items: center;
    justify-content: center;
  }
</style>