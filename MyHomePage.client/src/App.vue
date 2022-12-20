<template>

  <main class="container-fluid">
    <router-view />
  </main>
  <footer class="d-flex justify-content-center">

  
      <iframe src="https://widgets.media.sportradar.com/uscommon/en_us/standalone/us.match.nfl.liveMatchCarousel#border=false" frameborder="0" height="200" width="800"></iframe>
    
   
  </footer>
  
</template>

<script>
import { computed } from 'vue'
import { AppState } from './AppState'
import Navbar from './components/Navbar.vue'

export default {
  setup() {
    return {
      appState: computed(() => AppState)
    }
  },
  components: { Navbar }
}
</script>
<style lang="scss">
@import "./assets/scss/main.scss";

:root{
  --main-height: calc(100vh - 32px - 64px);
}


</style>
