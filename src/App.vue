<template>
  <div class="container">
    <header class="">
      <Navigation />
    </header>
    <main>
      <router-view></router-view>
    </main>
  </div>
</template>

<script>
import Navigation from './components/UI/Navigation'
export default {
  components: {
    Navigation
  },
};
</script>

<style></style>
