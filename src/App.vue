<template>
  <div id="app">
    <Navbar />
    <router-view/>
    <footer class="bg-primary py-5 flex justify-center">
      <img :src="require('@/assets/img/Smart-CT-White 1.png')" />
    </footer>
  </div>
</template>

<script>
// @
import Navbar from '@/components/Navbar.vue';

export default {
  name: 'App',
  components: {
    Navbar,
  },
};
</script>

<style>
.bg-primary {
  background: #ff5039;
}
.text-primary {
  color: #ff5039;
}
.bg-secondary {
  background: #87c540;
}
.text-secondary {
  color: #87c540;
}
.bg-tertiary {
  background: #410f35;
}
.text-tertiary {
  color: #410f35;
}
</style>
