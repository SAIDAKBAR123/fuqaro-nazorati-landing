<template>
  <v-row no-gutters>
    <v-col cols="12" class="my-0">
        <v-card color="white" tile flat class="white--text">
          <v-img class="align-center justify-center" height="100%" :src="bannerPath">
          <v-row justify="start" align="center">
            <v-col cols="auto" offset="1">
              <div style="height:150px; background: white; border: 6px solid white; border-radius: 10px"> </div>
            </v-col>
            <v-col cols="auto">
              <h1 class="text_layout">Fuqaro Nazorati sahifasiga xush kelibsiz </h1>
              <span class=" text_layout_small">Endilikda siz o'z muammo va takliflaringizni
                  onlayn tarzda ariza berish orqali amalga oshirishingiz mumkin. </span>
            </v-col>
            <v-col cols="12" offset="1">
              <v-btn elevation="0" rounded color="primary" x-large>Play Store</v-btn>
            </v-col>
          </v-row>
        </v-img>
        </v-card>
    </v-col>
  </v-row>
</template>

<script>
const bannerPath = require('../../assets/Images/back.png')
export default {
  data () {
    return {
      bannerPath
    }
  }
}
</script>

<style scoped>
 .overlay {
    position: relative;
    width: 100%;
    height: 100%;
    left: 0;
    top: 0;
    background: rgba(51,51,51,0.7);
    z-index: 10;
  }
  .text_layout {
    color: white;
    font-size: 6vh;
  }
  .text_layout_small {
    font-size: 1.2rem;
    color: white;
  }
</style>
