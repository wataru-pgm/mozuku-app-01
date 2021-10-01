<template>
  <div id="app">
    <v-app-bar color="brown darken-1">
      <v-toolbar-title>
        <router-link to="/">もずくあわせ</router-link> 
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <router-link to="/Manual">遊び方</router-link>
    </v-app-bar>
    <router-view/>
     <v-footer color="brown darken-1" app>
      2021.mozuku
    </v-footer>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
