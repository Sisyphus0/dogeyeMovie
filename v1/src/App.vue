<template>
  <div id="app">
    <v-header></v-header>
    <router-view></router-view>
  </div>
</template>

<script type="text/ecmascript-6">

import header from 'components/header/header.vue'

export default {
  name: 'app',
  components: {
    'v-header': header
  }
}
</script>

<style lang="sass">
</style>
