<template>
    <div>
        <div class="fixed" id="fixed">
            <h2><nuxt-link :to="{path:'/cambodian-genocide'}"> Cambodian Genocide </nuxt-link> </h2>
            <div class="menu" @click="toggleMenu">
              <i class="fa fa-bars"></i>
            </div>
        </div>
        <div class="dropdown--menu" v-if="isMenuOpen">
          <ul>
            <li>
              <nuxt-link :to="{path:'/cambodian-genocide/'}">Top</nuxt-link>
            </li>
            <li>
              <nuxt-link :to="{path:'/cambodian-genocide/cambodian-genocide/who'}">Who</nuxt-link>
            </li>
            <li>
              <nuxt-link :to="{path:'/cambodian-genocide/cambodian-genocide/what'}">What</nuxt-link>
            </li>
            <li>
              <nuxt-link :to="{path:'/cambodian-genocide/cambodian-genocide/influence/education'}">Education</nuxt-link>
            </li>
            <li>
              <nuxt-link :to="{path:'/cambodian-genocide/cambodian-genocide/influence/others'}">Other</nuxt-link>
            </li>
            <li>
              <nuxt-link :to="{path:'/cambodian-genocide/cambodian-genocide/influence/interview'}">Interview</nuxt-link>
            </li>
          </ul>
        </div>
        <div class="navbar">
            <img src="/cambodian-genocide/000030.JPG" style="width:100%;">
            <div class="centered">
                <h2><nuxt-link :to="{path:'/cambodian-genocide'}"> Cambodian Genocide </nuxt-link> </h2>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name:"Header",
  data() {
    return {
      isMenuOpen: false,
    }
  },
  mounted() {
    window.onscroll = () => {
      this.scrollFunction()
    };
  },
  methods: {
    scrollFunction() {
      if (document.body.scrollTop > 80 || document.documentElement.scrollTop > 80) {
        document.getElementById("fixed").style.display = "block";
      } else {
        document.getElementById("fixed").style.display = "none";
        this.isMenuOpen = false
      }
    },
    toggleMenu() {
      this.isMenuOpen = !this.isMenuOpen
    }
  },
}
</script>

<style scooped>

.navbar{
  position:relative;
}

.navbar .centered{
  position:absolute;
  background-color:#ffffff;
  opacity: 0.7;
  top:50%;
  left:50%;
  transform:translate(-50%,-50%);
  padding:35px;
  text-align:center;
}

.navbar .centered h2{
  font-family: "Times New Roman", Times, serif;
  text-align:center;
  font-size: 26px;
  font-weight:normal;
  color:#F0B49E;
}

.navbar .centered h2 a{
  color: #000000;
}

.fixed {
    position: fixed;
    z-index: 100;
    top: 0;
    left: 0;
    width: 100%;
    background: #000000;
    padding: 10px;
}

.fixed a{
    color: #ffffff;
}

h2{
    font-family: "Times New Roman", Times, serif;
}

.menu {
  position: absolute;
  top: 0;
  right: 0;
  height: 100%;
  width: 45px;
  text-align: center;
  line-height: 45px;
  color: #fff;
  cursor: pointer;
}

.dropdown--menu {
  position: fixed;
  top: 44px;
  left: 0;
  width: 100%;
  background: #000;
  z-index: 101;
}
.dropdown--menu ul li {
  border-bottom: solid 1px #222;
}
.dropdown--menu ul li:first-child {
  border-top: solid 1px #222;
}
.dropdown--menu ul li a {
  display: block;
  padding: 15px;
  color: #fff;
}
</style>
