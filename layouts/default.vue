<template>
  <v-app>
    <v-app-bar fixed app height="113" color="black">
      <Header />
    </v-app-bar>
    <v-main class="grey lighten-4 mb-2">
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
      <Footer />
    </v-main>
  </v-app>
</template>


