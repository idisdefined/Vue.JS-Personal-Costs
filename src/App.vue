<template>
  <v-app>
    <v-app-bar app flat color="teal">
      <v-btn to="/dashboard" :ripple="false" plain>Dashboard</v-btn>
      <v-btn to="/about" :ripple="false" plain>About</v-btn>
      <v-btn to="/calculator" :ripple="false" plain>Calculator</v-btn>
    </v-app-bar>
    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: 'App',

  data: () => ({
    // Can be used...
  })
}
</script>
