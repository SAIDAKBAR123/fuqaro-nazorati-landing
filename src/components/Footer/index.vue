<template>
  <div>
    <v-footer white padless justify-center>
      <v-card class="flex" flat justify-center tile>
        <v-row class="footr" center>
          <v-list>
            <v-list-item-group v-model="item" color="primary" class="footer-list">
              <v-list-item color="black" text-sm-center>
                <a href="#about" class="footer-links">Biz haqimizda</a>
              </v-list-item>
              <v-list-item color="black" text-sm-center>
                <a href="#hizmat" class="footer-links">Hizmat turlari</a>
              </v-list-item>
            </v-list-item-group>
          </v-list>
          <v-spacer></v-spacer>
          <div v-if="false" class="addrs">
            <!-- <v-img
              src="@/assets/google-play.png"
              height="50px"
              max-width="200px"
              right>
            </v-img> -->
            <p class="black-txt ma-10 ml-5">
              Manzil: Toshkent shahar, Chilonzor tumani, 203 uy.
            </p>
          </div>
        </v-row>
        <!-- <v-card-title class="">
          <v-spacer></v-spacer>
          <v-btn v-for="icon in icons" :key="icon" class="mx-4" dark icon>
            <v-icon size="24px">
              {{ icon }}
            </v-icon>
          </v-btn>
        </v-card-title> -->

        <v-card-text class="py-2 gray--text text-center">
          {{ new Date().getFullYear() }} —
          <a href="http://it-solutions.uz"><strong>ITsolutions</strong></a>
        </v-card-text>
      </v-card>
    </v-footer>
  </div>
</template>

<script>
export default {
  data () {
    return {
      item: ''
    }
  }
}
</script>

<style>
.addrs {
  padding-top: 15px;
}
.footr {
  max-width: 1690px;
  margin: 0 auto !important;
}
.footer-links {
  text-decoration: none;
}
@media (max-width: 1690px) {
  .footr {
    max-width: 1190px;
    margin: 0 auto !important;
  }
}
@media (max-width: 1190px) {
  .footr {
    max-width: 700px;
    margin: 0 auto !important;
  }
}
@media (max-width: 700px) {
  .footr {
    max-width: 300px;
    flex-direction: column;
    justify-content: center;
    align-content: center;
  }
  .v-sheet .v-list {
    margin: 0 auto;
  }
  .theme--light.v-image {
    margin: 0 auto;
  }
  p {
    margin: 0 auto;
  }
  .footer-list {
    margin: 0 auto;
  }
  .addrs {
    text-align: center;
  }
}
</style>
