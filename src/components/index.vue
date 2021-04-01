<template>
  <div style="width=100%">
    <v-row no-gutters justify="center">
      <v-col cols="12" class="my-0">
        <Toolbar />
      </v-col>
      <v-col cols="12" class="my-0">
        <Landing />
      </v-col>
      <v-col cols="12" class="my-2">
        <Statistics />
      </v-col>
      <v-col cols="12" class="my-2">
        <Mottos />
      </v-col>
    </v-row>
        <Footer />
  </div>
</template>

<script>
import Statistics from './Statistics'
import Mottos from './Mottos'
import Landing from './Landing'
import Toolbar from './Toolbar'
import Footer from '@/components/Footer'
export default {
  components: {
    Landing,
    Statistics,
    Mottos,
    Toolbar,
    Footer
  }
}
</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
