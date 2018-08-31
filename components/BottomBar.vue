<template>
  <div>
    <md-bottom-bar class="md-accent start-position" md-sync-route>
      <md-bottom-bar-item to="/" md-label="Home" md-icon="home"></md-bottom-bar-item>
      <md-bottom-bar-item to="/data" md-label="Posts" md-icon="/assets/icon-whatshot.svg"></md-bottom-bar-item>
      <md-bottom-bar-item to="/tasks" md-label="Favorites" md-icon="favorite"></md-bottom-bar-item>
    </md-bottom-bar>
  </div>
</template>

<script>
  export default {
    name: 'BottomBar'
  }
</script>

<style lang="scss" scoped>
  .start-position {
    margin-left: 45%;
  }
</style>