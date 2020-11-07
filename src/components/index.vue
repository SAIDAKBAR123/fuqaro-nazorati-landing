<template>
  <div>
    <v-row no-gutters justify="center">
      <v-col cols="12" class="my-0">
        <Toolbar />
      </v-col>
      <v-col cols="12"  class="my-0">
        <Landing />
      </v-col>
      <v-col cols="12"  class="my-0">
        <Statistics />
      </v-col>
    </v-row>
  </div>
</template>

<script>
import Statistics from './Statistics'
import Landing from './Landing'
import Toolbar from './Toolbar'
export default {
  components: {
    Landing,
    Statistics,
    Toolbar
  }
}
</script>

<style>
</style>
