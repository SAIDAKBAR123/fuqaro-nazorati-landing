<template>
  <v-app width="100%">
    <v-main>
      <router-view></router-view>
    </v-main>
    <Footer />
  </v-app>
</template>

<script>
import Footer from './components/Footer'
export default {
  name: 'App',
  components: {
    Footer
  },
  created () {
    document.title = 'Fuqaro-nazorati'
    this.$vuetify.theme.themes.light.primary = '#34A696'
  },
  data: () => ({
    //
  })
}
</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
