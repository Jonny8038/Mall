<template>
  <div id="app">
    <div id="nav">
      <router-link to="/login"></router-link>
    </div>
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'app',
}
</script>
<style>
</style>
