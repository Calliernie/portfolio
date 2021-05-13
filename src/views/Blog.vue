<template>
  <div class="blog">
    <v-parallax
      class="para"
      style="height: 200px; opacity: 1"
      gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.9)"
      dark
      src="../assets/blog.jpg"
    >
      <v-overlay value="true" absolute>
        <v-row align="center" justify="center">
          <v-col class="text-center" cols="12">
            <h1 class="display-1 font-weight-thin mb-4"><b>Blog</b></h1>
          </v-col>
        </v-row>
      </v-overlay>
    </v-parallax>

    <v-row class="py-4 px-8">
      <v-col
        cols="12"
        xs="12"
        sm="6"
        md="4"
        lg="3"
        v-for="article in articles"
        :key="article.title"
      >
        <!-- <v-card color="transparent" class="pa-2">
          <v-card>
            <v-img :src="article.image"></v-img>
          </v-card>
        </v-card> -->

        <v-card class="mx-auto my-2" max-width="">
          <v-img
            height="250"
            src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
          ></v-img>
        </v-card>

        <span>30 minutes</span>
        <span class="float-right">SUPER EASY</span>

        <h4>Baked sweet potatoes with creamy avocado and pumpkin</h4>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  data() {
    return {
      articles: [
        { title: "Green veggies with flavoured butter", body: "lorem ipsum" },
        {
          title: "Baked sweet potatoes with creamy avocado and pumpkin",
          body: "lorem ipsum",
        },
        { title: "Green veggies with flavoured butter", body: "lorem ipsum" },
        {
          title: "Baked sweet potatoes with creamy avocado and pumpkin",
          body: "lorem ipsum",
        },
        { title: "Green veggies with flavoured butter", body: "lorem ipsum" },
      ],
    };
  },
};
</script>

<style scoped>
.gallery {
  width: 100%;
  height: 100%;
  background-image: url("../assets/background.png");
  background-size: cover;
  background-position: center;
  position: relative;
  overflow: hidden;
}

.transparent {
  height: 200px;
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
