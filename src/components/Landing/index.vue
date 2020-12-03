<template>
  <div class="header-container">
    <div class="header-title">
      <div style="height: 170px; width: 10px; background: white; border: 6px solid white; border-radius: 10px" class="header-decor"></div>
      <div class="header-title-info">
        <h1 class="text_layout">Fuqaro Nazorati sahifasiga xush kelibsiz</h1>
        <span class="text_layout_small font-weight-light"
          >Endilikda siz o'z muammo va takliflaringizni <br />
          onlayn tarzda ariza berish orqali amalga oshirishingiz mumkin.
        </span>
        <v-btn rounded color="primary" x-large width="200px"><v-icon left>mdi-google-play</v-icon>Play Store</v-btn>
      </div>
    </div>

    <div class="header-chat">
      <img src="../../assets/banner/photo_2020-12-01_13-30-27.jpg" alt="Amira-picture" width="190" height="180" class="pic amira-pic" />
      <img src="../../assets/banner/photo_2020-12-01_13-30-32.jpg" alt="Anora-picture" width="150" height="140" class="pic anora-pic" />
      <img src="../../assets/banner/sb.png" alt="Risolat-picture" width="150" height="140" class="pic risolat-pic" />
      <img src="../../assets/banner/photo_2020-12-01_13-30-00.jpg" alt="Kamron-picture" width="150" height="140" class="pic kamron-pic" />
      <img src="../../assets/banner/photo_2020-12-01_13-30-21.jpg" alt="sb-picture" width="90" height="90" class="pic sb-pic" />

      <div class="savol-1">
        <p>Assalomu alaykum, hurmatli tashkilot hodimlari hozirgi muammoni qay holatda hal qilib bera olasizlar? Qancha vaqt ichida hal qilib bera olasizlar?</p>
        <div class="triangle-1"></div>
      </div>
      <div class="savol-2">
        <p>Assalomu alaykum, hurmatli tashkilot hodimlari hozirgi muammoni qay holatda hal qilib bera olasizlar?</p>
        <div class="triangle-2"></div>
      </div>
    </div>
  </div>
</template>

<script>
// const bannerPath = require("../../assets/Images/back.png");
export default {
  data () {
    return {
      // bannerPath,
    }
  }
}
</script>

<style scoped>
* {
  box-sizing: 0;
  margin: 0;
  padding: 0;
}
.header-container {
  margin: 0;
  padding: 0;
  display: flex;
  background: url("../../assets/Images/back.png");
  background-repeat: no-repeat;
  background-size: cover;
  height: 1000px;
  justify-content: start;
  align-items: center;
  width: 100%;
  position: relative;
}

.header-title {
  display: grid;
  grid-template-columns: auto auto;
  column-gap: 15px;
  padding: 20px;
  margin-left: 70px;
}

.header-title-info {
  display: grid;
  grid-template-columns: auto;
  row-gap: 10px;
}

.header-chat {
  position: absolute;
  top: 5px;
  right: 12px;
}
/* banner pictures */
.amira-pic {
  position: absolute;
  top: 700px;
  right: 660px;
}
.anora-pic {
  position: absolute;
  top: 720px;
  right: 260px;
}
.risolat-pic {
  position: absolute;
  top: 480px;
  right: 490px;
}
.kamron-pic {
  position: absolute;
  top: 480px;
  right: 140px;
}
.sb-pic {
  position: absolute;
  top: 340px;
  right: 320px;
}

.pic {
  border-radius: 50%;
  border: 8px solid white;
  object-fit: cover;
}

/* end banner pictures */

.savol-1 {
  box-sizing: border-box;
  background-color: rgba(52, 166, 150, 0.3);
  width: 350px;
  position: absolute;
  position: relative;
  top: 750px;
  right: 870px;
  color: white;
  font-size: 12px;
  padding: 10px;
  border-radius: 10px;
}

.savol-2 {
  position: relative;
  box-sizing: border-box;
  background-color: rgba(52, 166, 150, 0.3);
  width: 350px;
  top: 790px;
  right: 100px;
  color: white;
  font-size: 12px;
  padding: 10px;
  border-radius: 10px;
}

.triangle-1 {
  position: absolute;
  height: 0px;
  width: 0px;
  top: 14px;
  right: -14px;
  z-index: 9999;
  border-top: 10px solid transparent;
  border-bottom: 10px solid transparent;
  border-left: 14px solid rgba(52, 166, 150, 0.3);
}

.triangle-2 {
  position: absolute;
  height: 0px;
  width: 0px;
  top: -14px;
  right: 300px;
  z-index: 1;
  border-left: 10px solid transparent;
  border-right: 10px solid transparent;
  border-bottom: 14px solid rgba(52, 166, 150, 0.3);
}

@media (max-width: 400px) {
  .header-decor {
    display: none;
  }
  .text_layout {
    font-size: 20px;
  }
}

@media (min-width: 1400px) and (max-width: 1700px) {
  .header-chat {
    top: -12px;
    right: 30px;
  }
  .risolat-pic {
   top: 561px;
   right: 446px;
  }

  .kamron-pic {
    top: 561px;
    right: 90px;
  }

  .anora-pic {
    top: 720px;
    right: 330px;
  }
  .sb-pic {
    top: 390px;
    right: 250px;
  }
  .savol-2 {
    right: 190px;
  }
}

@media (min-width: 1280px) and (max-width: 1399px) {
   .header-chat {
    top: -3px;
    right: 6px;
  }
  .risolat-pic {
    top: 619px;
    right: 480px;
  }

  .kamron-pic {
    top: 530px;
    right: 200px;
  }

  .anora-pic {
    top: 720px;
    right: 330px;
  }
  .sb-pic {
    display: none;
  }
  .savol-2 {
    right: 190px;
  }
}

@media (min-width: 1132px) and (max-width: 1279px) {
   .header-chat {
    top: -79px;
    right: 4px
  }

  .risolat-pic {
    display: none;
  }

  .kamron-pic {
    top: 530px;
    right: 111px;
  }

  .amira-pic {
    top: 700px;
    right: 585px;
  }
  .anora-pic {
    top: 720px;
    right: 330px;
  }

  .savol-1 {
    right: 795px;
  }

  .savol-2 {
    right: 180px;
  }
  .sb-pic {
    display: none;
  }
}

@media (min-width: 1031px) and (max-width: 1131px) {
  .header-chat {
    top: 51px;
    right: 19px;
  }

  .risolat-pic {
    display: none;
  }
  .kamron-pic {
    display: none;
  }
  .sb-pic {
    display: none;
  }

  .amira-pic {
    right: 460px;
    top: 647px;
  }
  .savol-1 {
    right: 667px;
  }
  .anora-pic {
    top: 512px;
  }
  .savol-2 {
    right: 94px;
    top: 580px;
  }
}

@media (max-width: 1030px) {
  .header-chat {
    display: none;
  }
  .header-container {
    margin-bottom: 100px;
  }
}

.text_layout {
  color: white;
  font-size: 45px;
}
.text_layout_small {
  font-size: 25px;
  color: white;
}
</style>
