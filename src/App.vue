<template>
  <v-app>
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
    this.$vuetify.theme.themes.light.primary = '#34A696'
  },
  data: () => ({
    //
  })
}
</script>
