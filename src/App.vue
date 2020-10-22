<template>
  <div id="app">
    <Navbar />
    <router-view/>
    <footer class="bg-tertiary py-5">
      <div class="flex flex-col items-center container mx-auto lg:px-20 px-5">
        <img class="mx-auto" :src="require('@/assets/img/Smart-CT-White 1.png')" />
        <div class="flex justify-center">
          <p class="text-white text-sm py-2 font-light">
            This work and its contents by SmartCitiesPH, Inc. is licensed under a Creative Commons
            Attribution-NonCommercial-ShareAlike 4.0 International License. Other works (software,
            source code, etc.) referenced in this website are under their own respective licenses.
            This site is powered by Jekyll and hosted on Github (view source)
          </p>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
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
