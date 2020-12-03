<template>
  <v-card  class="templates" color= "white" tile flat max-width="1690">
      <h2 class=" text-left">Ilova haqida</h2>
      <div style="width:100px; background: #34A696; border: 4px solid #34A696; border-radius: 10px"> </div>
      <div>
        <p  class="text-container"> Loyiha hozirgi vaqtda amalga oshirilgan ilgor texnologiya orqali
          yurtimizdagi oma va boshqa tur vakillari va ularning turdosh qismlarini
          oz ichiga olish bilan bir qatorda tuzilgan. Tizim orqali siz istalgan raqam
          egasini aniqlash imkoniyatiga ega bol
        </p>
      </div>
      <div class="template-box_container">
        <v-img
          height="540"
          max-width="305"
          src='../../assets/Images/Rectangle 49@1X.png'>
        </v-img>
          <div>
            <h2 class="text_layout"> Template 1.</h2>
            <p  class="text-container"> Loyiha hozirgi vaqtda amalga oshirilgan ilgor texnologiya orqali
              yurtimizdagi oma va boshqa tur vakillari va ularning turdosh qismlarini
              oz ichiga olish bilan bir qatorda tuzilgan. Tizim orqali siz istalgan raqam
              egasini aniqlash imkoniyatiga ega bol
            </p>
          </div>

      </div>
      <div class="template-box_container">

          <div>
            <h2 class="text_layout"> Template 2.</h2>
            <p  class="text-container"> Loyiha hozirgi vaqtda amalga oshirilgan ilgor texnologiya orqali
              yurtimizdagi oma va boshqa tur vakillari va ularning turdosh qismlarini
              oz ichiga olish bilan bir qatorda tuzilgan. Tizim orqali siz istalgan raqam
              egasini aniqlash imkoniyatiga ega bol
            </p>
          </div>
           <v-img
              height="540"
              max-width="305"
              src='../../assets/Images/Rectangle 49@1X.png'>
            </v-img>

      </div>
      <div class="template-box_container">
        <v-img
          height="540"
          max-width="305"
          src='../../assets/Images/Rectangle 49@1X.png'>
        </v-img>
          <div>
            <h2 class="text_layout"> Template 3.</h2>
            <p  class="text-container"> Loyiha hozirgi vaqtda amalga oshirilgan ilgor texnologiya orqali
              yurtimizdagi oma va boshqa tur vakillari va ularning turdosh qismlarini
              oz ichiga olish bilan bir qatorda tuzilgan. Tizim orqali siz istalgan raqam
              egasini aniqlash imkoniyatiga ega bol
            </p>
          </div>

      </div>

  </v-card>
</template>

<script>
export default {

}
</script>

<style scoped>
.templates{
  margin: auto 10%;

}

.text-container{
  max-width: 700px;
  margin-top: 35px;
}
.template-box_container{
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1215px;
  margin: 100px auto;

}
.green-box{
  width: 30px;
  height: 540px;
  content: "";
}

</style>
