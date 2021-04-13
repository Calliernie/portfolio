<template>
  <v-app-bar dense depressed dark app>
    <v-app-bar-title class="text-uppercase grey--text">
      <v-btn text router to="/">
        <span>Calli</span>
        <span class="yellow--text">Ernie</span>
      </v-btn>
    </v-app-bar-title>

    <v-spacer></v-spacer>

    <v-btn text color="grey" router to="/gallery" class="mx-1"> Gallery </v-btn>
    <v-btn text color="grey" router to="/profile" class="mx-1"> Profile </v-btn>
    <v-btn text color="grey" router to="/blog" class="mx-1"> Blog </v-btn>
    <v-btn text color="grey" router to="/shop" class="mx-1"> Shop </v-btn>
  </v-app-bar>
</template>
