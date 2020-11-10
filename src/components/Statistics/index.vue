<template>
  <v-card class="my-2" max-height="1200" color="white" tile flat>
    <!-- <h2 class="text-center">Mavluda Part</h2> -->
    <v-row class="row-layout">
      <v-col class="col-layout-1">
        <p class="p-title">Loyiha haqida qisqacha ma'lumot</p>
        <div class="shape"></div>
        <p>
          Loyiha hozirgi vaqtda amalga oshirilgan ilg'or texnologiya orqali
          yurtimizdagi oma va boshqa tur vakillari va ularning turdosh
          qismlarini o'z ichiga olish bilan bir qatorda tuzilgan. Tizim orqali
          siz istalgan raqam egasini aniqlash imkoniyatiga ega bolgan holatda
          alam qiladigan holat yuzasidan shikoyat.
        </p>

        <v-list class="list-items">
          <v-list-item
            ><v-icon class="icons">mdi-checkbox-marked-circle-outline</v-icon
            >Muammoni doimiy monitoringi</v-list-item
          >
          <v-list-item
            ><v-icon class="icons">mdi-checkbox-marked-circle-outline</v-icon
            >Hal etilmagan ustidan ariza</v-list-item
          >
          <v-list-item
            ><v-icon class="icons">mdi-checkbox-marked-circle-outline</v-icon
            >Doimiy muloqot</v-list-item
          >
          <v-list-item
            ><v-icon class="icons">mdi-checkbox-marked-circle-outline</v-icon
            >Bonuslar</v-list-item
          >
        </v-list>
        <v-btn text class="batafsil_btn"
          >Batafsil<v-icon class="icons">mdi-arrow-right</v-icon></v-btn
        >
      </v-col>
      <v-col>
        <v-img
          src="../../assets/Images/phone.png"
          alt="phone image"
          class="phone_img"
          width="300"
          height="500"
        >
        </v-img>
      </v-col>
    </v-row>
  </v-card>
</template>

<script>
export default {}
</script>

<style scoped>
.row-layout {
  padding-left: 50px;
  padding-top: 50px;
  column-gap: 100px;
  font-size: 10pt;
  height: 600px;
}

.col-layout-1 {
  padding-left: 60px;
  padding-right: 70px;
}
.p-title {
  margin-top: 30px;
  margin-bottom: 5px;
  font-weight: 600;
  font-size: 16pt;
  letter-spacing: 1px;
}

.batafsil_btn {
  margin-top: 40px;
  width: 150px;
  height: 60px;
  padding: 15px 10px 15px 10px;
  background-color: rgba(52, 166, 150, 0.14);
  text-align: center;
  color: #34a696;
  text-transform: capitalize;
}
.list-items {
  font-weight: 600;
}
.icons {
  color: #34a696;
  padding: 10px;
  font-size: 22px;
}

.shape {
  margin-top: 0;
  margin-bottom: 15px;
  width: 160px;
  height: 5px;
  background-color: #34a696;
}
</style>
