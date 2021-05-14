<template>
  <div class="hero">
    <div class="content">
      <small class="yellow--text" style="font-size: 20px">Welcome to my</small>
      <h1 class="white--text">Calliernie</h1>
      <v-btn text outlined class="outline white--text tourBtn" type="button"
        >Take a tour</v-btn
      >
    </div>

    <!-- <div class="side-bar" v-show="side_nav"> -->
    <div class="social-links hidden-xs-only">
      <a
        target="_blank"
        href="https://www.facebook.com"
        style="text-decoration: none"
      >
        <v-btn fab small text class="my-2"
          ><v-icon class="white--text">mdi-facebook</v-icon></v-btn
        >
      </a>

      <a
        target="_blank"
        href="https://www.twitter.com"
        style="text-decoration: none"
      >
        <v-btn fab small text class="my-2"
          ><v-icon class="white--text">mdi-twitter</v-icon></v-btn
        >
      </a>

      <a
        target="_blank"
        href="https://www.linkedin.com"
        style="text-decoration: none"
      >
        <v-btn fab small text class="my-2"
          ><v-icon class="white--text">mdi-linkedin</v-icon></v-btn
        >
      </a>

      <a
        target="_blank"
        href="https://www.instagram.com"
        style="text-decoration: none"
      >
        <v-btn fab small text class="my-2"
          ><v-icon class="white--text">mdi-instagram</v-icon></v-btn
        >
      </a>
    </div>

    <div class="bubbles">
      <img src="../assets/bubble.png" />
      <img src="../assets/bubble.png" />
      <img src="../assets/bubble.png" />
      <img src="../assets/bubble.png" />
      <img src="../assets/bubble.png" />
      <img src="../assets/bubble.png" />
      <img src="../assets/bubble.png" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
  data() {
    return {
      side_nav: true,
    };
  },
};
</script>

<style>
.hero {
  width: 100%;
  height: 100%;
  background-image: url("../assets/diff.jpg");
  background-size: cover;
  background-position: center;
  position: relative;
  overflow: hidden;
}
.outline {
  border: thin solid white;
}
.content {
  position: absolute;
  top: 32%;
  left: 8%;
  transform: translateY(-50);
  z-index: 2;
}

h1 {
  font-size: 80px;
  margin: 10px 0 30px;
  line-height: 80px;
}

.side-bar {
  width: 50px;
  height: 100%;
  background: url("../assets/diff.jpg");
  /* background: linear-gradient(#00545d, #000729); */
  position: absolute;
  right: 0;
  top: 0;
}

.menu {
  display: block;
  width: 25px;
  margin: 40px auto 0;
  cursor: pointer;
}

.social-links img,
.useful-links img {
  width: 30px;
  margin: 5px auto;
  cursor: pointer;
}

.social-links {
  width: 50px;
  text-align: center;
  position: absolute;
  top: 30%;
  transform: translateX(-50);
  transform: translateY(-50);
  right: 1%;
  align-content: center;
}

.useful-links {
  width: 50px;
  text-align: center;
  position: absolute;
  top: 50%;
  transform: translateY(-50);
}

.bubbles img {
  width: 50px;
  animation: bubble 7s linear infinite;
}

.bubbles {
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: space-around;
  position: absolute;
  bottom: -70px;
}

@keyframes bubble {
  0% {
    transform: translateY(0);
    opacity: 0;
  }
  50% {
    opacity: 1;
  }
  70% {
    opacity: 1;
  }
  100% {
    transform: translateY(-80vh);
    opacity: 0;
  }
}

.bubbles img:nth-child(1) {
  animation-delay: 2s;
  width: 25px;
}
.bubbles img:nth-child(2) {
  animation-delay: 1s;
}
.bubbles img:nth-child(3) {
  animation-delay: 3s;
  width: 25px;
}
.bubbles img:nth-child(4) {
  animation-delay: 4.5s;
}
.bubbles img:nth-child(5) {
  animation-delay: 3s;
}
.bubbles img:nth-child(6) {
  animation-delay: 6s;
  width: 20px;
}
.bubbles img:nth-child(7) {
  animation-delay: 7s;
  width: 35px;
}
.tourBtn {
  border-color: white !important;
}
</style>
