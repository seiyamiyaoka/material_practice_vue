<template>
  <div>
    <sidever />
    <nuxt/>
    <bottom-bar />
  </div>
</template>
<script>
import Sidever from '../components/Sidever'
import BottomBar from '../components/BottomBar'
export default {
  components: {
    Sidever,
    BottomBar
  }
}
</script>
