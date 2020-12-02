<template>
  <v-card class="templates  mt-10" color="white" tile flat max-width="1690">
    <h2 class="text-left">Ilova haqida</h2>
    <div
      style="width:100px; background: #34A696; border: 4px solid #34A696; border-radius: 10px"
    ></div>
    <div>
      <p class="text-about">
        Loyiha hozirgi vaqtda amalga oshirilgan ilgor texnologiya orqali
        yurtimizdagi oma va boshqa tur vakillari va ularning turdosh qismlarini
        oz ichiga olish bilan bir qatorda tuzilgan. Tizim orqali siz istalgan
        raqam egasini aniqlash imkoniyatiga ega bol
      </p>
    </div>
    <div class="template-box_container">
      <div class="rectangle instruction-1"></div>
      <div class="text-container">
        <h2 class="text_layout">Template 1.</h2>
        <p>
          Loyiha hozirgi vaqtda amalga oshirilgan ilgor texnologiya orqali
          yurtimizdagi oma va boshqa tur vakillari va ularning turdosh
          qismlarini oz ichiga olish bilan bir qatorda tuzilgan. Tizim orqali
          siz istalgan raqam egasini aniqlash imkoniyatiga ega bol
        </p>
      </div>
    </div>
    <div class="template-box_container">
      <div class="text-container">
        <h2 class="text_layout">Template 1.</h2>
        <p>
          Loyiha hozirgi vaqtda amalga oshirilgan ilgor texnologiya orqali
          yurtimizdagi oma va boshqa tur vakillari va ularning turdosh
          qismlarini oz ichiga olish bilan bir qatorda tuzilgan. Tizim orqali
          siz istalgan raqam egasini aniqlash imkoniyatiga ega bol
        </p>
      </div>
      <div class="rectangle instruction-2"></div>
    </div>
    <div class="template-box_container">
      <div class="rectangle instruction-3"></div>
      <div class="text-container">
        <h2 class="text_layout">Template 1.</h2>
        <p>
          Loyiha hozirgi vaqtda amalga oshirilgan ilgor texnologiya orqali
          yurtimizdagi oma va boshqa tur vakillari va ularning turdosh
          qismlarini oz ichiga olish bilan bir qatorda tuzilgan. Tizim orqali
          siz istalgan raqam egasini aniqlash imkoniyatiga ega bol
        </p>
      </div>
    </div>
      <div class="template-box_container">
      <div class="text-container">
        <h2 class="text_layout">Template 1.</h2>
        <p>
          Loyiha hozirgi vaqtda amalga oshirilgan ilgor texnologiya orqali
          yurtimizdagi oma va boshqa tur vakillari va ularning turdosh
          qismlarini oz ichiga olish bilan bir qatorda tuzilgan. Tizim orqali
          siz istalgan raqam egasini aniqlash imkoniyatiga ega bol
        </p>
      </div>
       <div class="rectangle instruction-4"></div>
    </div>

    <!----------------- Biz bilan hamkorlar --------------->
    <!-- <div class="parters-block">
      <h2 class=" text-left">Biz bilan hamkorlar</h2>
      <div
        style="width:150px; background: #34A696; border: 4px solid #34A696; border-radius: 10px"
      ></div>
      <div class="partners-body">
        <div class="listofPartners-block">
          <ul>
            <ol>
              Shurchi tumani
            </ol>
            <ol>
              Shurchi tumani
            </ol>
            <ol>
              Shurchi tumani
            </ol>
            <ol>
              Shurchi tumani
            </ol>
          </ul>
        </div>
        <div class="map-block">
          <v-img
            height="auto"
            width="100%"
            src="../../assets/Images/map-picture.png"
          >
          </v-img>
        </div>
      </div>
    </div> -->
     <!----------------- Biz asosiy maqsadimiz --------------->
    <v-row color="#E2E2E2">
      <div class="goals-block" style="margin: 15% auto;">
        <h2 class=" text-center">Bizning asosiy maqsadimiz</h2>
        <p class=" text-center">
          Contrary to popular belief, Lorem Ipsum is not simply random text. It
          has roots in a piece of classical Latin literature from 45 BC, making
          it over 2000 years old. Richard McClintock, a Latin professor at
          Hampden-Sydney College
        </p>
        <div class="grid-container">
          <div class="grid-item">
            <v-img
              height="101"
              width="103"
              class="mx-auto"
              src="../../assets/Images/document.png"
            >
            </v-img>
            <h4>Fuqarolar faolligi</h4>
            <p>
            Fuqaro Nazorati bu fuqarolar hayotida sodir bo’ladigan turli xil muammolarini bartaraf</p>
          </div>
          <div class="grid-item">
            <v-img
              height="101"
              width="103"
              class="mx-auto"
              src="../../assets/Images/police.png"
            >
            </v-img>
            <h4>Hokimiyat</h4>
            <p>
              Tushib keladigan murojaatlarni hokimiyat va mutasaddi tashkilot tomonidan ko’rib chiqlib bartaraf etiladi
            </p>
          </div>
          <div class="grid-item">
            <v-img
              height="101"
              width="103"
              class="mx-auto"
              src="../../assets/Images/pdf-pic.png"
            >
            </v-img>
            <h4>Murojaatlar </h4>
            <p>
              Fuqarolarga hokimiyat va mutasaddi tashkilotlardan muntazam ravishda murojaat bo’yicha hisobot onlayn rejimda beriladi.
            </p>
          </div>
        </div>
        <!----------------- Bizning asosiy maqsadimiz --------------->
        <div class="mail-block">
          <h1>
            Oxirgi yangiliklardan behabar qolmaslik uchun quyidagi email
            formasini toldiring va biz bilan birga bo'ling!
          </h1>
          <div class="mail-input">
            <!--   <input v-model="email" label="Email" placeholder="Email kiriting" class="input-field"> -->
            <v-text-field
              :rules="rules"
              label="Emailni kiriting"
              solo
              height="50"
              max-width="770"
            ></v-text-field>
            <!-- <v-btn :disabled="!valid" color="#34A696" width="163" height="57">
            Jo'natish
          </v-btn> -->

            <v-btn
              color="primary"
              elevation="3"
              depressed
              height="50"
              width="25%"
            >
              Jo'natish
            </v-btn>
          </div>
        </div>
      </div>
    </v-row>
  </v-card>
</template>

<script></script>

<style>
/* Ilova Haqida */

.templates {
  margin: auto 10%;
}
.rectangle {
  height: 550px;
  width: 35%;
  background-size: contain;
  background-position: center;
  background-repeat: no-repeat;
  border-radius:5%;
}
.text-left{
  font-size: 30px;
}
.instruction-1{
  background-image: url("../../assets/1.png");
}
.instruction-2{
  background-image: url("../../assets/2.png");
}
.instruction-3{
  background-image: url("../../assets/3.png");
}
.instruction-4{
  background-image: url("../../assets/4.png");
}
.text-about {
  width: 70%;
  margin-top: 5%;
  font-size: 24px;
}
.text-container {
  max-width: 60%;
  margin-top: 5%;
}
.template-box_container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1215px;
  margin: 15% auto;
}
.green-box {
  width: 30px;
  height: 540px;
  content: "";
}
@media (max-width: 1450px) {
  .grid-container .grid-item p,
  h4 {
    font-size: 18px;
  }
}
@media (max-width: 1024px) {
  .goals-block .grid-container {
    grid-template-columns: none !important;
    grid-template-rows: auto auto auto;
  }
}
@media screen and (max-width: 650px) {
  .text_layout,
  .text-left,
  .text-center {
    font-size: 18px;
  }
  .rectangle {
    height: 300px;
  }
  .partners-body {
    flex-direction: column;
  }
  .partners-body .listofPartners-block,
  .partners-body .map-block {
    width: 100%;
  }
  .mail-block h1 {
    font-size: 16px;
  }
  .v-btn__content {
    font-size: 10px;
  }
  .text-about {
    width: 100%;
    margin-top: 3%;
    font-size: 14px;
}
}
@media screen and (max-width: 350px) {
  .text-container {
    font-size: 10px;
  }
}

/*------------- Biz bilan hamkorlar ------------*/
.parters-block {
  max-width: 1690px;
}
.partners-body {
  display: flex;
  justify-content: space-between;
}
.listofPartners-block,
.map-block {
  margin-top: 5%;
  width: 45%;
}
.listofPartners-block ul {
  border: 1px solid #e2e2e2;
  padding: 0;
}
.listofPartners-block ul ol {
  padding: 5%;
  border-bottom: 1px solid #e2e2e2;
}
.listofPartners-block ul ol:hover {
  background-color: #34a696;
  transition: 0.2s;
}
.goals-block p {
  max-width: 80%;
  margin: 5% auto;
}
.grid-container {
  display: grid;
  grid-template-columns: auto auto auto;
  max-width: 100%;
  margin: 5% auto;
  justify-content: space-between;
  align-content: center;
}
.grid-item {
  display: flex;
  flex-direction: column;
  justify-content: center;
  background-color: rgba(255, 255, 255, 0.8);
  box-shadow: 0 2px 4px 0 rgba(0, 0, 0, 0.3);
  padding: 5%;
  font-size: 30px;
  text-align: center;
}
.grid-item p {
  max-width: 100%;
  font-size: 23px;
}

/* ------------Bizning asosiy maqsadimiz--------------- */
.mail-block {
  max-width: 1184px;
  margin: 15% auto;
  text-align: center;
  background-color: white;
  border-radius: 10px;
  padding: 10%;
  padding-bottom: 0;
  margin-bottom: 0;
}
.mail-input {
  display: flex;
  max-width: 100%;
  margin: 0px auto;
  margin-top: 15%;
  justify-content: center;
}
.input-field {
  background-color: #f8f8f8;
  height: 57px;
  width: 70%;
  border: none;
}
.input-field:placeholder {
  padding-left: 5%;
}
.v-input {
  margin: 0;
}
.v-input input {
  height: 57px;
}
</style>
