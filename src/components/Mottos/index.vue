<template>
  <v-card class="templates" color="white" tile flat max-width="1690">
    <h2 class=" text-left">Ilova haqida</h2>
    <div
      style="width:100px; background: #34A696; border: 4px solid #34A696; border-radius: 10px"
    ></div>
    <div>
      <p class="text-container">
        Loyiha hozirgi vaqtda amalga oshirilgan ilgor texnologiya orqali
        yurtimizdagi oma va boshqa tur vakillari va ularning turdosh qismlarini
        oz ichiga olish bilan bir qatorda tuzilgan. Tizim orqali siz istalgan
        raqam egasini aniqlash imkoniyatiga ega bol
      </p>
    </div>
    <div class="template-box_container">
      <v-img
        height="540"
        max-width="305"
        src="../../assets/Images/Rectangle 49@1X.png"
      >
      </v-img>
      <div>
        <h2 class="text_layout">Template 1.</h2>
        <p class="text-container">
          Loyiha hozirgi vaqtda amalga oshirilgan ilgor texnologiya orqali
          yurtimizdagi oma va boshqa tur vakillari va ularning turdosh
          qismlarini oz ichiga olish bilan bir qatorda tuzilgan. Tizim orqali
          siz istalgan raqam egasini aniqlash imkoniyatiga ega bol
        </p>
      </div>
    </div>
    <div class="template-box_container">
      <div>
        <h2 class="text_layout">Template 2.</h2>
        <p class="text-container">
          Loyiha hozirgi vaqtda amalga oshirilgan ilgor texnologiya orqali
          yurtimizdagi oma va boshqa tur vakillari va ularning turdosh
          qismlarini oz ichiga olish bilan bir qatorda tuzilgan. Tizim orqali
          siz istalgan raqam egasini aniqlash imkoniyatiga ega bol
        </p>
      </div>
      <v-img
        height="540"
        max-width="305"
        src="../../assets/Images/Rectangle 49@1X.png"
      >
      </v-img>
    </div>
    <div class="template-box_container">
      <v-img
        height="540"
        max-width="305"
        src="../../assets/Images/Rectangle 49@1X.png"
      >
      </v-img>
      <div>
        <h2 class="text_layout">Template 3.</h2>
        <p class="text-container">
          Loyiha hozirgi vaqtda amalga oshirilgan ilgor texnologiya orqali
          yurtimizdagi oma va boshqa tur vakillari va ularning turdosh
          qismlarini oz ichiga olish bilan bir qatorda tuzilgan. Tizim orqali
          siz istalgan raqam egasini aniqlash imkoniyatiga ega bol
        </p>
      </div>
    </div>

    <div class="parters-block">
      <h2 class=" text-left">Biz bilan hamkorlar</h2>
      <div
        style="width:200px; background: #34A696; border: 4px solid #34A696; border-radius: 10px"
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
            height="550"
            width="700"
            min-height="200"
            min-width="300"
            src="../../assets/Images/map-picture.png"
          >
          </v-img>
        </div>
      </div>
    </div>
    <v-row color="#E2E2E2">
      <div class="goals-block" style="margin: 200px auto;">
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
            <h4>Lorem isn sra</h4>
            <p>
              Contrary to popular belief, Lorem Ipsum is not simply random text.
              It has roots in a piece of classical Latin literature from 45 BC,
              making it over 2000 years old. Richard McClintock, a Latin
              professor at Hampden-Sydney College
            </p>
          </div>
          <div class="grid-item">
            <v-img
              height="101"
              width="103"
              class="mx-auto"
              src="../../assets/Images/police.png"
            >
            </v-img>
            <h4>Lorem isn sra</h4>
            <p>
              Contrary to popular belief, Lorem Ipsum is not simply random text.
              It has roots in a piece of classical Latin literature from 45 BC,
              making it over 2000 years old. Richard McClintock, a Latin
              professor at Hampden-Sydney College
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
            <h4>Lorem isn sra</h4>
            <p>
              Contrary to popular belief, Lorem Ipsum is not simply random text.
              It has roots in a piece of classical Latin literature from 45 BC,
              making it over 2000 years old. Richard McClintock, a Latin
              professor at Hampden-Sydney College
            </p>
          </div>
        </div>
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

            <v-btn color="primary" elevation="3" depressed height="50">
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
.templates {
  margin: auto 10%;
}
.text-container {
  max-width: 700px;
  margin-top: 35px;
}
.template-box_container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1215px;
  margin: 100px auto;
}
.green-box {
  width: 30px;
  height: 540px;
  content: "";
}
.parters-block {
  max-width: 1690px;
}
.partners-body {
  display: flex;
  justify-content: space-between;
}
.listofPartners-block {
  margin-top: 38px;
}
.listofPartners-block ul {
  width: 630px;
  border: 1px solid #e2e2e2;
}
.listofPartners-block ul ol {
  height: 84px;
  padding: 20px 30px;
  border-bottom: 1px solid #e2e2e2;
}
.listofPartners-block ul ol:hover {
  background-color: #34a696;
  transition: 0.2s;
}
.goals-block p {
  max-width: 1100px;
  margin: 90px auto;
}
.grid-container {
  display: grid;
  grid-template-columns: auto auto auto;
  max-width: 1600px;
  justify-content: space-between;
  align-content: center;
}
.grid-item {
  display: flex;
  flex-direction: column;
  justify-content: center;
  background-color: rgba(255, 255, 255, 0.8);
  box-shadow: 0 2px 4px 0 rgba(0, 0, 0, 0.3);
  padding: 20px;
  font-size: 30px;
  text-align: center;
}
.grid-item p {
  max-width: 400px;
  margin: 20px;
  font-size: 23px;
}
.mail-block {
  max-width: 1184px;
  margin: 50px auto;
  text-align: center;
  background-color: white;
  border-radius: 10px;
  padding: 30px;
}
.mail-input {
  display: flex;
  max-width: 850px;
  margin: 0px auto;
  margin-top: 100px;
  justify-content: center;
}
.input-field {
  background-color: #f8f8f8;
  height: 57px;
  width: 770px;
  border: none;
}
.input-field:placeholder {
  padding-left: 10px;
}
.v-input {
  margin: 0;
}
.v-input input {
  height: 57px;
}
.v-input input::la {
  height: 57px;
}
</style>
