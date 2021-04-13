<template>
  <div class="gallery grey lighten-4">
    <!-- <v-parallax
      class="para"
      style="height: 200px; opacity: 1"
      gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.9)"
      dark
      src="../assets/profile3.jpg"
    >
      <v-overlay value="true" absolute>
        <v-row align="center" justify="center">
          <v-col class="text-center" cols="12">
            <h1 class="display-1 font-weight-thin mb-4">
              <b>Welcome to the shop</b>
            </h1>
          </v-col>
        </v-row>
      </v-overlay>
    </v-parallax> -->

    <v-img style="height: 100%" src="../assets/comingSoon.jpg"></v-img>
  </div>
</template>

<style scoped>
.gallery {
  width: 100%;
  height: 100%;
  /* background-image: url("../assets/background.png"); */
  background-size: cover;
  background-position: center;
  position: relative;
  overflow: hidden;
}

.transparent {
  height: 170px;
}

.innerCard {
  height: 185px;
}

.img {
  height: 185px;
}
/* .outCard {
  background-color: transparent !important;
  border-color: transparent !important;
} */
</style>
