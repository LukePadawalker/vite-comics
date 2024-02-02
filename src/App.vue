<script setup>
import AppHeader from './components/AppHeader.vue'
import AppBlueBar from './components/AppBlueBar.vue'
import AppContent from './components/AppContent.vue'
import AppFooter from './components/AppFooter.vue'
import { dcFilms, headerVoices } from './assets/data/index.js'

export default {
  data: () => ({
    dcFilms,
    headerVoices,
  })
};
</script>

<template>
  <AppHeader />
  <AppContent />
  <AppBlueBar />
  <AppFooter />
</template>

<style lang="scss" scoped>
// generics
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  list-style-type: none;
}

.logo {
  height: 6em;
  will-change: filter;
  transition: filter 300ms;

}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
