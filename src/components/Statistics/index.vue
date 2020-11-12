<template>
  <div>
    <div class="loyiha-haqida-container">
      <div>
        <p class="loyiha-title">Loyiha haqida qisqacha ma'lumot</p>
        <div class="shape"></div>
        <p>
          Loyiha hozirgi vaqtda amalga oshirilgan ilg'or texnologiya orqali
          yurtimizdagi oma va boshqa tur vakillari va ularning turdosh
          qismlarini o'z ichiga olish bilan bir qatorda tuzilgan. Tizim orqali
          siz istalgan raqam egasini aniqlash imkoniyatiga ega bolgan holatda
          alam qiladigan holat yuzasidan shikoyat.
        </p>

        <div>
          <v-list class="list-items">
            <v-list-item>
              <v-icon class="icons">mdi-checkbox-marked-circle-outline</v-icon
              >Muammoni doimiy monitoringi
            </v-list-item>
            <v-list-item>
              <v-icon class="icons">mdi-checkbox-marked-circle-outline</v-icon
              >Hal etilmagan ustidan ariza
            </v-list-item>
            <v-list-item>
              <v-icon class="icons">mdi-checkbox-marked-circle-outline</v-icon
              >Doimiy muloqot
            </v-list-item>
            <v-list-item>
              <v-icon class="icons">mdi-checkbox-marked-circle-outline</v-icon
              >Bonuslar
            </v-list-item>
          </v-list>
        </div>
        <v-btn text class="batafsil_btn"
          >Batafsil<v-icon class="icons">mdi-arrow-right</v-icon>
        </v-btn>
      </div>
      <div class="loyiha-image-container">
        <img
          src="../../assets/Images/phone.png"
          alt="phone image"
          class="phone_img"
        />
      </div>
    </div>

    <!--Statistika -->
    <div class="statistika-container">
      <div class="stats-info">
        <p>Statistika</p>
        <div class="shape s-shape"></div>
        <p>
          Loyiha hozirgi vaqtda amalga oshirilgan ilgor texnologiya orqali
          yurtimizdagi oma va boshqa tur vakillari va ularning turdosh
          qismlarini oz ichiga olish bilan bir qatorda tuzilgan. Tizim orqali
          siz istalgan raqam egasini aniqlash imkoniyatiga ega bol.
        </p>
        <p class="input-title">Ko'chani tanlang</p>
        <v-row class="d-flex align-baseline">
          <v-col>
            <v-select :items="items" solo></v-select>
          </v-col>
          <v-col>
            <v-btn text class="show-btn" height="48px">Ko'rsatish</v-btn>
          </v-col>
        </v-row>
      </div>

      <div class="statistika-right-container">
        <div>
          <p>Umumiy</p>
          <p>3234</p>
        </div>
        <div>
          <p>Jarayonda</p>
          <p>453</p>
        </div>
        <div>
          <p>Hal etilgan</p>
          <p>234</p>
        </div>
        <div>
          <p>Rad etilgan</p>
          <p>234</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// export default {};
//
</script>
<script>
export default {
  data: () => ({
    items: ["Foo", "Bar", "Fizz", "Buzz"]
  })
};
</script>

<style scoped>
/*start loyiha haqida qisqacha ma'lumot */

.loyiha-haqida-container {
  padding: 30px;
  padding-left: 60px;
  display: grid;
  grid-template-columns: minmax(200px, 600px) minmax(200px, 600px);
  grid-template-rows: minmax(200px, 600px);
  align-items: center;
  justify-content: space-between;
}

.loyiha-title {
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
  width: 21%;
  height: 5px;
  background-color: #34a696;
}

.loyiha-image-container {
  display: grid;
  justify-content: center;
}

.phone_img {
  max-width: 400px;
  max-height: 500px;
}

@media (max-width: 760px) {
  .loyiha-haqida-container {
    grid-template-columns: minmax(200px, 500px);
    grid-template-rows: minmax(200px, 500px) minmax(200px, 650px);
    padding: 20px;
  }
}

/*end loyiha haqida qisqacha ma'lumot */
/* start statistika part */

.statistika-container {
  background-image: url("../../assets/Images/map2.png");
  background-size: contain;
  background-repeat: no-repeat;
  background-size: 100% 100%;
  margin: 0;
  padding: 30px;
  padding-left: 70px;
  display: grid;
  grid-template-columns: minmax(500px, 600px) minmax(400px, 600px);
  justify-content: space-between;
}

.s-shape {
  width: 11.5%;
}

.statistika-right-container {
  display: grid;
  grid-template-columns: minmax(50px, 180px) minmax(50px, 180px);
  grid-template-rows: minmax(10px, 180px) minmax(10px, 180px);
  column-gap: 20px;
  row-gap: 20px;
  justify-content: center;
}

.statistika-right-container > div {
  padding-top: 20px;
  background-color: #fff;
  opacity: 1;
  text-align: center;
  font-weight: 600;
}

.statistika-right-container > div > p:nth-child(1) {
  font-size: 25px;
}

.statistika-right-container > div > p:nth-child(2) {
  font-size: 40px;
  color: #4dd1a8;
  opacity: 1;
}

.stats-info {
  padding-top: 40px;
}

.stats-info > p:nth-child(1) {
  font-size: 16pt;
  font-weight: 600;
  margin-bottom: 0;
}

.stats-info > p:nth-child(3) {
  padding-top: 30px;
  font-size: 10pt;
}

.input-title {
  margin-top: 40px;
  margin-bottom: 0;
  font-size: 10pt;
}

.show-btn {
  background-color: #34a696;
  color: white;
}

@media (min-width: 930px) and (max-width: 1100px) {
  .statistika-right-container > div > p:nth-child(1) {
    font-size: 15px;
  }

  .statistika-right-container > div > p:nth-child(2) {
    font-size: 20px;
  }

  .statistika-right-container {
    grid-template-columns: 150px 150px;
    grid-template-rows: 150px 150px;
  }
}

@media (max-width: 930px) {
  .statistika-container {
    padding: 30px;
    grid-template-columns: minmax(200px, 600px);
    grid-template-rows: minmax(200px 900px) minmax(200px, 900px);
    align-items: center;
    justify-content: center;
  }
}

/* end statistika part */
</style>
