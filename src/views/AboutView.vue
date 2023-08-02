<template>
  <div class="about">
    <Home/>
  </div>
</template>

<script>
import Home from '@/components/Home.vue';
export default {
  name: 'AboutView',
  components: {
    Home,
  }
}
</script>

<style scoped>
.about {
  width: 100%;
}
</style>