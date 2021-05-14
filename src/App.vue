<template>
  <v-app>
    <v-navigation-drawer app dark temporary v-model="sideNav">
      <v-list>
        <v-list-item :to="item.link" v-for="item in menuItems" :key="item.title"
          ><v-list-item-action>
            <v-icon left> {{ item.icon }} </v-icon></v-list-item-action
          >
          <v-list-item-content> {{ item.title }} </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
    <v-app-bar dense depressed dark app>
      <v-app-bar-title class="text-uppercase grey--text">
        <v-btn text router to="/">
          <span>Calli</span>
          <span class="yellow--text">Ernie</span>
        </v-btn>
      </v-app-bar-title>

      <v-spacer></v-spacer>

      <v-btn
        left
        small
        fab
        text
        @click.native.stop="sideNav = !sideNav"
        class="hidden-sm-and-up"
        ><v-icon>mdi-menu</v-icon></v-btn
      >

      <div class="hidden-xs-only">
        <v-btn text color="grey" router to="/gallery" class="mx-1">
          Gallery
        </v-btn>
        <v-btn text color="grey" router to="/profile" class="mx-1">
          Profile
        </v-btn>
        <v-btn text color="grey" router to="/blog" class="mx-1"> Blog </v-btn>
        <v-btn text color="grey" router to="/shop" class="mx-1"> Shop </v-btn>
      </div>
    </v-app-bar>
    <v-main>
      <router-view></router-view>
    </v-main>
    <v-footer padless dark class="hidden-sm-and-up">
      <v-card flat tile width="100%" class="gray lighten-4 text-center">
        <v-card-text>
          <a
            target="_blank"
            href="https://www.facebook.com"
            style="text-decoration: none"
          >
            <v-btn class="mx-4" icon>
              <v-icon size="24px">mdi-facebook</v-icon>
            </v-btn>
          </a>
          <a
            target="_blank"
            href="https://www.twitter.com"
            style="text-decoration: none"
          >
            <v-btn class="mx-4" icon>
              <v-icon size="24px">mdi-twitter</v-icon>
            </v-btn>
          </a>
          <a
            target="_blank"
            href="https://www.linkedin.com"
            style="text-decoration: none"
          >
            <v-btn class="mx-4" icon>
              <v-icon size="24px">mdi-linkedin</v-icon>
            </v-btn>
          </a>
          <a
            target="_blank"
            href="https://www.instagram.com"
            style="text-decoration: none"
          >
            <v-btn class="mx-4" icon>
              <v-icon size="24px">mdi-instagram</v-icon>
            </v-btn>
          </a>
        </v-card-text>
      </v-card>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      sideNav: false,
      menuItems: [
        { icon: "mdi-home", title: "Home", link: "/" },
        { icon: "mdi-image-multiple", title: "Gallery", link: "/gallery" },
        { icon: "mdi-face", title: "Profile", link: "/profile" },
        { icon: "mdi-post-outline", title: "Blog", link: "/blog" },
        { icon: "mdi-cart", title: "Shop", link: "/shop" },
      ],
      icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
      links: [
        "https://www.facebook.com",
        "https://www.twitter.com",
        "https://www.linkedin.com",
        "https://www.instagram.com",
      ],
    };
  },
};
</script>
