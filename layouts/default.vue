<template>
  <div class="body">
    <AppHeader />
    <Nuxt/>
  </div>
</template>

<script>
import AppHeader from '../components/AppHeader';

export default {
  components: {
    AppHeader
  }
}
</script>

<style>
body {
  padding: 100px;
}
</style>