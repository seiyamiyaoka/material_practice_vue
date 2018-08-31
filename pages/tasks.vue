<template>
<div class="page-container">
    <md-app>

<!-- ここからコンテンツ -->
      <md-app-content>
        <elevation dataSize=4 />
      </md-app-content>
    </md-app>
  </div>
</template>

<script>
import Elevation from '../components/Elavation'
export default {
  name: 'Reveal',
  data: () => ({
    dataSize: 4
  }),
  components: {
    Elevation
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
