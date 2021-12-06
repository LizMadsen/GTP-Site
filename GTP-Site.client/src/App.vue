<template>
  <header>
    <Navbar />
  </header>
  <main>
    <router-view />
  </main>
  <footer>
    <center>
      <div class="bg-dark tex-light p-3">
        Made by Liz, December 2021
      </div>
    </center>
  </footer>
</template>

<script>
  import { computed } from 'vue'
  import { AppState } from './AppState'
  export default {
    name: 'App',
    setup() {
      return {
        appState: computed(() => AppState)
      }
    }
  }
</script>
<style lang="scss">
  @import "./assets/scss/main.scss";
</style>