<template>
<v-card class="my-2" max-height="3200" color="white" tile flat>
    <!-- <h2 class="text-center">Mavluda Part</h2> -->
    <!--Loyiha haqida qisqacha ma'lumot -->
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
                <v-list-item>
                    <v-icon class="icons">mdi-checkbox-marked-circle-outline</v-icon>Muammoni doimiy monitoringi
                </v-list-item>
                <v-list-item>
                    <v-icon class="icons">mdi-checkbox-marked-circle-outline</v-icon>Hal
                    etilmagan ustidan ariza
                </v-list-item>
                <v-list-item>
                    <v-icon class="icons">mdi-checkbox-marked-circle-outline</v-icon>Doimiy muloqot
                </v-list-item>
                <v-list-item>
                    <v-icon class="icons">mdi-checkbox-marked-circle-outline</v-icon>Bonuslar
                </v-list-item>
            </v-list>
            <v-btn text class="batafsil_btn">Batafsil<v-icon class="icons">mdi-arrow-right</v-icon>
            </v-btn>
        </v-col>
        <v-col>
            <v-img src="../../assets/Images/phone.png" alt="phone image" class="phone_img" width="300" height="500">
            </v-img>
        </v-col>
    </v-row>
    <!--Statistika -->

    <v-row class="statistika">
        <v-col class="stats-info">
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
        </v-col>
        <v-col>
            <v-row class="grid-container">
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
            </v-row>
        </v-col>
    </v-row>
</v-card>
</template>

<script>
// export default {};
//
</script><script>
export default {
    data: () => ({
        items: ["Foo", "Bar", "Fizz", "Buzz"]
    })
};
</script>

<style scoped>
/*start loyiha haqida qisqacha ma'lumot */

.row-layout {
    padding-left: 150px;
    padding-top: 50px;
    column-gap: 100px;
    font-size: 10pt;
    height: 700px;
}

.col-layout-1 {
    padding-left: 40px;
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
    width: 21%;
    height: 5px;
    background-color: #34a696;
}

/*end loyiha haqida qisqacha ma'lumot */
/* start statistika part */

.statistika {
    margin: 0;
    padding-left: 170px;
    width: 100%;
    background-image: url("../../assets/Images/map2.png");
    background-repeat: no-repeat;
    background-size: contain;
    height: 780px;
    column-gap: 50px;
    letter-spacing: 1px;

}

.s-shape {
    width: 11.5%;
}

.grid-container {
    padding-top: 40px;
    display: grid;
    grid-template-columns: minmax(50px, 200px) minmax(50px, 200px);
    grid-template-rows: minmax(50px, 200px) minmax(50px, 200px);
    column-gap: 25px;
    row-gap: 25px;
}

.grid-container>div {
    padding-top: 20px;
    background-color: #fff;
    opacity: 1;
    text-align: center;
    font-weight: 600;
}

.grid-container>div>p:nth-child(1) {
    font-size: 25px;
}

.grid-container>div>p:nth-child(2) {
    font-size: 40px;
    color: #4dd1a8;
    opacity: 1;
}

.stats-info {
    padding-top: 40px;
}

.stats-info>p:nth-child(1) {
    font-size: 16pt;
    font-weight: 600;
    margin-bottom: 0;
}

.stats-info>p:nth-child(3) {
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

/* end statistika part */
</style>
