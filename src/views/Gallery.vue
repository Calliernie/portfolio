<template>
  <div class="gallery grey lighten-4">
    <v-parallax
      class="para"
      style="height: 200px; opacity: 1"
      gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.9)"
      dark
      src="../assets/5.jpg"
    >
      <v-overlay value="true" absolute>
        <v-row align="center" justify="center">
          <v-col class="text-center" cols="12">
            <h1 class="display-1 font-weight-thin mb-4">Gallery</h1>
          </v-col>
        </v-row>
      </v-overlay>
    </v-parallax>

    <!-- <div class="rightScroll"> -->
    <!-- first block -->
    <v-row class="py-4 px-8">
      <v-col
        cols="12"
        xs="12"
        sm="6"
        md="4"
        lg="3"
        v-for="image in images"
        :key="image.path"
      >
        <v-card color="transparent" class="pa-2">
          <v-card>
            <v-img :src="image.path"></v-img>
          </v-card>
        </v-card>
      </v-col>
    </v-row>

    <!-- <div class="bubbles">
      <img src="../assets/bubble.png" />
      <img src="../assets/bubble.png" />
      <img src="../assets/bubble.png" />
      <img src="../assets/bubble.png" />
      <img src="../assets/bubble.png" />
      <img src="../assets/bubble.png" />
      <img src="../assets/bubble.png" />
    </div> -->
  </div>
</template>

<script>
export default {
  data() {
    return {
      images: [
        { path: "/background.png" },
        { path: "/background.png" },
        { path: "/background.png" },
        { path: "/background.png" },
        { path: "/background.png" },
        { path: "/background.png" },
        { path: "/background.png" },
        { path: "/background.png" },
        { path: "/background.png" },
      ],
    };
  },
};
</script>

<style scoped>
.gallery {
  width: 100%;
  height: 100%;
  /* background-image: url("../assets/gee.jpg"); */
  background-size: cover;
  background-position: center;
  position: relative;
  overflow: hidden;
}

.transparent {
  height: 200px;
}

.rightScroll {
  flex: 1;
  height: 560px;
  overflow-y: scroll; /* it works! */
}

.innerCard {
  height: 185px;
}

.img {
  height: 185px;
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
/* .outCard {
  background-color: transparent !important;
  border-color: transparent !important;
} */
</style>
