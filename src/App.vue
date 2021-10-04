<template>
  <v-app id="app">
    <v-app-bar color="brown lighten-4" fixed>
      <v-toolbar-title>
        <router-link to="/">もずくあわせ</router-link> 
      </v-toolbar-title>

        <v-spacer></v-spacer>

     
      <router-link to="/Manual">遊び方</router-link>
    </v-app-bar>
<h1>Playarea画面</h1>
    <router-view/>

    <v-footer color="brown lighten-4" app>
      2021.mozuku
    </v-footer>
  </v-app>
</template>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
