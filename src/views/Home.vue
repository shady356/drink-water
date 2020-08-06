<template>
  <div class="home">
    <h1>Drink Water</h1>
    <Wave
      color="#64baff"
      class="wave"
    />
  </div>
</template>

<script>
import Wave from '@/components/effects/wave.vue'
export default {
  name: 'Home',
  components: {
    Wave
  }
}
</script>

<style lang="scss" scoped>
  .home {
    position: fixed;
    width: 100vw;
    height: 100vh;
    top: 0;
    left: 0;

    .wave {
      left: 0;
      bottom:0;
      position: absolute;
      width: 100%;
    }
  }
</style>
