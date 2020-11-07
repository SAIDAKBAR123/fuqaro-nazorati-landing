<template>
 <v-app-bar
      fixed
      dark
      color="#34a69757"
      elevate-on-scroll
      scroll-target="#scrolling-techniques-7"
    >
      <v-app-bar-nav-icon v-if="false"></v-app-bar-nav-icon>

      <v-toolbar-title class="ml-2">Fuqaro <br> Nazorati</v-toolbar-title>

      <v-spacer></v-spacer>

    <v-row v-if="FALSE" justify="center">
      <v-col cols="auto" class="mx-3" v-for="item in routes" :key="item.title">
          <a href="#" class="target_a" v-html="item.title" />
      </v-col>
    </v-row>
        <v-toolbar-items class="hidden-sm-and-down">
      <v-btn text  v-for="item in routes" :key="item.title" class=" text-capitalize" v-text="item.title" />
        </v-toolbar-items>
     <v-spacer></v-spacer>
    <v-btn color="primary" elevation="0">Kirish</v-btn>
    </v-app-bar>
</template>

<script>
export default {
  data () {
    return {
      routes: [
        {
          title: 'Texnik tavsilot',
          route: '#about'
        },
        {
          title: 'Biz haqimizda',
          route: '#about'
        },
        {
          title: 'Statistika',
          route: '#about'
        },
        {
          title: 'Hizmatlar',
          route: '#about'
        },
        {
          title: 'Aloqa',
          route: '#about'
        }
      ]
    }
  },
  methods: {
    getInfo (e) {
      console.log(e)
    }
  }
}
</script>

<style scoped>
.target_a {
  color: white;
  text-decoration: none
}
</style>
