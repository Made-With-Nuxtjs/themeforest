<template>
  <v-app >
    <v-app-bar 
      app
      height="113"
       color="black"
    >
      <Header />
    </v-app-bar>

    <v-main class="grey lighten-2 mb-2">
      <v-container>
        <v-row>
          <v-col cols="12" sm="10" offset-sm="1">      
              <v-row>
                <v-col>
                  <Nuxt />
                </v-col>
              </v-row>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<style scoped>
.bg{
  background-color: rgb(43, 40, 40);
}
</style>

