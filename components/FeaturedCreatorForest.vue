<template>
  <v-container>
    <v-row class="mt-10 grey lighten-5">
      <h1 class="pa-5 text--secondary">Featured creator</h1>

      <v-row>
        <v-col cols="3">
          <v-card
            class="d-flex"
            :color="$vuetify.theme.dark ? 'grey darken-3' : 'grey lighten-4'"
            flat
            tile
          >
            <v-card flat class="pa-5">
              <img
                width="80"
                height="80"
                src="https://0.s3.envato.com/files/188354408/logo80x80.png"
                alt="dan_fisher"
              />
            </v-card>
            <v-card flat class="py-5">
              <h2 class="text--secondary">dan_fisher</h2>
              <h4 class="text--primary font-weight-light">
                Member since August 2010
              </h4>
              <nuxt-link to="#" class="text-decoration-none">
                <v-btn
                  elevation="10"
                  tile
                  color="success"
                  class="text-capitalize mt-2"
                >
                  View protfolio
                </v-btn>
              </nuxt-link>
            </v-card>
          </v-card>
        </v-col>
        <v-col cols="9">
          <h3 class="px-7 text--secondary">
            Our themes and templates are produced by world-class creators (or
            Authors, as we call them). Explore the best of the week.
          </h3>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="6" sm="4" md="4">
          <v-card class="mx-auto pb-2 mb-4 mr-0" width="95%">
            <div class="mb-2">
              <v-carousel
                height="200"
                hide-delimiter-background
                show-arrows-on-hover
              >
                <v-carousel-item
                  v-for="(item, i) in items"
                  :key="i"
                  :src="item.src"
                ></v-carousel-item>
              </v-carousel>
            </div>
            <v-card flat>
              <h4 class="ml-3">
                <nuxt-link to="#" class="text-decoration-none black--text"
                  >Necromancers - eSports & Gaming Team WordPress
                  Theme</nuxt-link
                >
              </h4>
              <nuxt-link to="#" class="text-decoration-none">
                <h5 class="text--primary font-weight-light ml-3 mb-3">
                  by dan_fisher in Entertainment
                </h5>
              </nuxt-link>
              <h3 class="ml-3 text--secondary">$45</h3>

              <v-card class="d-flex justify-space-between" flat tile>
                <v-card class="px-3" flat tile>
                  <h5 class="text--secondary">
                    <v-rating
                      v-model="rating"
                      background-color="white"
                      color="yellow accent-4"
                      dense
                      half-increments
                      hover
                      size="15"
                    ></v-rating>
                  </h5>

                  <h5 class="text--secondary">32 Sales</h5>
                </v-card>
                <v-card class="px-3 pb-1" flat tile dense>
                  <v-btn elevation="2" outlined>
                    <v-icon> mdi-cart</v-icon></v-btn
                  >
                  <v-btn
                    elevation="2"
                    outlined
                    class="text-capitalize"
                    color="#12A4E5"
                  >
                    Preview</v-btn
                  >
                </v-card>
              </v-card>
            </v-card>
          </v-card>
        </v-col>
        <v-col cols="6" sm="4" md="4">
          <v-card class="mx-auto pb-2 mb-4" width="95%">
            <div class="mb-2">
              <v-carousel
                height="200"
                hide-delimiter-background
                show-arrows-on-hover
              >
                <v-carousel-item
                  v-for="(item, i) in items"
                  :key="i"
                  :src="item.src"
                ></v-carousel-item>
              </v-carousel>
            </div>
            <v-card flat>
              <h4 class="ml-3">
                <nuxt-link to="#" class="text-decoration-none black--text"
                  >Necromancers - eSports & Gaming Team WordPress
                  Theme</nuxt-link
                >
              </h4>
              <nuxt-link to="#" class="text-decoration-none">
                <h5 class="text--primary font-weight-light ml-3 mb-3">
                  by dan_fisher in Entertainment
                </h5>
              </nuxt-link>
              <h3 class="ml-3 text--secondary">$45</h3>

              <v-card class="d-flex justify-space-between" flat tile>
                <v-card class="px-3" flat tile>
                  <h5 class="text--secondary">
                    <v-rating
                      v-model="rating"
                      background-color="white"
                      color="yellow accent-4"
                      dense
                      half-increments
                      hover
                      size="15"
                    ></v-rating>
                  </h5>

                  <h5 class="text--secondary">31 Sales</h5>
                </v-card>
                <v-card class="px-3 pb-1" flat tile dense>
                  <v-btn elevation="2" outlined>
                    <v-icon> mdi-cart</v-icon></v-btn
                  >
                  <v-btn
                    elevation="2"
                    outlined
                    class="text-capitalize"
                    color="#12A4E5"
                  >
                    Preview</v-btn
                  >
                </v-card>
              </v-card>
            </v-card>
          </v-card>
        </v-col>
        <v-col cols="6" sm="4" md="4">
          <v-card class="mx-auto pb-2 mb-4 ml-0" width="95%">
            <div class="mb-2">
              <v-carousel
                height="200"
                hide-delimiter-background
                show-arrows-on-hover
              >
                <v-carousel-item
                  v-for="(item, i) in items"
                  :key="i"
                  :src="item.src"
                ></v-carousel-item>
              </v-carousel>
            </div>
            <v-card flat>
              <h4 class="ml-3">
                <nuxt-link to="#" class="text-decoration-none black--text"
                  >Necromancers - eSports & Gaming Team WordPress
                  Theme</nuxt-link
                >
              </h4>
              <nuxt-link to="#" class="text-decoration-none">
                <h5 class="text--primary font-weight-light ml-3 mb-3">
                  by dan_fisher in Entertainment
                </h5>
              </nuxt-link>
              <h3 class="ml-3 text--secondary">$45</h3>

              <v-card class="d-flex justify-space-between" flat tile>
                <v-card class="px-3" flat tile>
                  <h5 class="text--secondary">
                    <v-rating
                      v-model="rating"
                      background-color="white"
                      color="yellow accent-4"
                      dense
                      half-increments
                      hover
                      size="15"
                    ></v-rating>
                  </h5>

                  <h5 class="text--secondary">31 Sales</h5>
                </v-card>
                <v-card class="px-3 pb-1" flat tile dense>
                  <v-btn elevation="2" outlined>
                    <v-icon> mdi-cart</v-icon></v-btn
                  >
                  <v-btn
                    elevation="2"
                    outlined
                    class="text-capitalize"
                    color="#12A4E5"
                  >
                    Preview</v-btn
                  >
                </v-card>
              </v-card>
            </v-card>
          </v-card>
        </v-col>
      </v-row>
    </v-row>
  </v-container>
</template>
<script>
export default {
  data: () => ({
    rating: 4.3,
    items: [
      {
        src: 'images/caro1.jpg',
      },
      {
        src: 'https://cdn.vuetifyjs.com/images/carousel/sky.jpg',
      },
      {
        src: 'images/caro2.jpg',
      },
      {
        src: 'images/caro3.png',
      },
      {
        src: 'https://cdn.vuetifyjs.com/images/carousel/planet.jpg',
      },
    ],
  }),
}
</script>

<style scoped>
.theme--light.v-btn.v-btn--has-bg {
  background-color: inherit;
}
.v-card--reveal {
  align-items: center;
  bottom: 0;
  justify-content: center;
  position: absolute;
  width: 100%;
}
.truncate-overflow {
  overflow: hidden;
  text-overflow: ellipsis;
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-line-clamp: 1;
  white-space: normal;
}
</style>