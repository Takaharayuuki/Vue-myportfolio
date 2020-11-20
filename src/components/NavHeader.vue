<template>
<v-card class="overflow-hidden">
    <v-app-bar
      absolute
      color="white"
      elevate-on-scroll
      scroll-target="#scrolling-techniques-7"
    >
      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-toolbar-title>Takahara yuukiのポートフォリオ</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>

      <v-btn icon>
        <v-icon>mdi-heart</v-icon>
      </v-btn>

      <v-btn icon>
        <v-icon>mdi-dots-vertical</v-icon>
      </v-btn>
    </v-app-bar>
    <v-sheet
      id="scrolling-techniques-7"
      class="overflow-y-auto"
      max-height="600"
    >
      <v-container style="height: 1500px;">
      </v-container>
    </v-sheet>
  </v-card>
<!-- <v-app-bar prominent>
  <header>
    <div id="nav">
      <h1></h1>
      <router-link to="/">Home<font-awesome-icon icon="home"/></router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/works">Works</router-link> |
      <router-link to="/contact">Contact</router-link>
    </div>
  </header>
</v-app-bar> -->
</template>

<script>
export default {
  name: "NavHeader"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.v-card {
  font-family: 'Raleway', sans-serif;
}
</style>