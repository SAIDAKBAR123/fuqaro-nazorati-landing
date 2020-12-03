<template>
  <nav class="navbar">
    <div class="logo">
      <p>
        Fuqaro <br />
        Nazorati
      </p>
    </div>
    <a href="" class="toggle-button" @click.prevent="toggleButton()"><v-icon style="color: white">mdi-menu</v-icon></a>
    <div class="navbar-links" v-bind:class="{ active: isActive }">
      <ul>
        <li><a href="#">Texnik Tavsilot</a></li>
        <li><a href="#about">Biz Haqimizda</a></li>
        <li><a href="#statistic">Statistika</a></li>
        <li><a href="#">Hizmatlar</a></li>
        <li><a href="#">Aloqa</a></li>
        <!--<li>
          <a href=""><v-icon style="color: rgb(43 129 197)">mdi-web</v-icon><v-icon style="color: rgb(43 129 197)">mdi-menu-down-outline</v-icon></a>
        </li>-->
      </ul>
    </div>
    <div class="navbar-button" :class="{ active: isActive }">
      <v-btn color="#34a696" class="white--text">Kirish</v-btn>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Toolbar',

  data () {
    return {
      isActive: false
    }
  },

  methods: {
    setLocale (locale) {
      this.$i18n.locale = locale
      localStorage.setItem('locale', locale)
    },

    toggleButton () {
      this.isActive = !this.isActive
    }
  }
}
</script>

<style scoped>
* {
  box-sizing: border-box;
}

.navbar {
  padding: 0;
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  position: fixed;
  z-index: 111;
  background-color: rgba(52, 166, 150, 0.3);
}

.logo {
  font-family: "Poppins", serif, "Poppins", serif !important;
  margin-left: 30px;
  margin-top: 3px;
  font-size: 1.25rem;
  line-height: 1.5;
  color: white;
}

.logo > p {
  margin: 0;
  padding: 0;
}

.navbar-links ul {
  display: flex;
  align-items: baseline;
  padding-right: 20px;
  margin: 0;
}

.navbar-links ul li {
  list-style: none;
  transition: background 0.3s ease 0s;
  margin: 0;
}

.navbar-links ul li:hover {
  background: rgba(52, 166, 150, 0.1);
}

.navbar-links ul li a {
  text-decoration: none;
  color: white;
  font-family: "Poppins", serif, "Poppins", serif !important;
  text-transform: capitalize;
  font-size: 0.875rem;
  font-weight: 500;
  letter-spacing: 0.0892857143em;
  padding: 1.5rem;
  display: block;
  margin: 0;
}
.navbar-button {
  display: flex;
  padding-right: 20px;
}

.toggle-button {
  text-decoration: none;
  position: absolute;
  top: 15px;
  right: 15px;
  display: none;
}

@media (max-width: 950px) {
  .navbar-button {
    display: none;
  }
  .toggle-button {
    display: block;
  }
  .navbar-links {
    display: none;
  }

  .navbar {
    padding-bottom: 10px;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
  }

  .navbar-links {
    margin: 0;
    padding: 0;
    width: 100%;
  }
  .navbar-links ul {
    width: 100%;
    flex-direction: column;
    padding: 0;
    margin: 0;
  }
  .navbar-links li {
    width: 100%;
    text-align: center;
  }
  .navbar-links ul > li > a {
    padding: 6px;
  }
  .navbar-button {
    width: 100%;
    justify-content: center;
    padding-right: 0;
  }

  .navbar-links.active {
    display: flex;
  }
  .navbar-button.active {
    display: flex;
  }
}
</style>
