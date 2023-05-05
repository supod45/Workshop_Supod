<template>
  <div id="app">
    <template>
  <v-card
    class="overflow-hidden mx-auto"
    height="10"
    max-width="650"
  >
    <v-bottom-navigation
      absolute
      hide-on-scroll
      horizontal
      scroll-target="#hide-on-scroll-example"
    >
      <v-btn
        color="deep-purple accent-4"
        text
      >
        <router-link to="/">Profile</router-link> |

        <v-icon>mdi mdi-account-box</v-icon>
      </v-btn>

      <v-btn
        color="deep-purple accent-4"
        text
      >
     <router-link to="/page1">Contact</router-link> |

        <v-icon>mdi-heart</v-icon>
      </v-btn>

      <v-btn
        color="deep-purple accent-4"
        text
      >
  <router-link to="/page2">Project</router-link> |

        <v-icon>mdi mdi-book</v-icon>
      </v-btn>
    </v-bottom-navigation>

    <v-responsive
      id="hide-on-scroll-example"
      class="overflow-y-auto"
      max-height="600"
    >
      <v-responsive height="1500"></v-responsive>
    </v-responsive>
  </v-card>
</template>
    <router-view />
  </div>
</template>

<script>
export default {
   name: 'App',

   data: () => ({
      //
   })
}

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.router-link-exact-active {
  color: blue;
}
</style>