<template>
  <v-container>
    <v-row class="mt-16 pt-13">
      <v-col cols="12" sm="4" md="4">
        <v-card
          class="d-flex align-center grey lighten-5 mb-4"
          flat
          height="100%"
          tile
        >
          <v-card flat tile>
            <h1 class="ml-8 pa-7">Featured themes</h1>
            <h3 class="ml-8 px-7 text--secondary">
              Every week, our staff personally hand-pick some of the best new
              website themes from our collection.
            </h3>
            <v-row align="center" class="pl-5 ma-10">
              <nuxt-link to="" class="text-decoration-none">
                <v-btn
                  elevation="10"
                  tile
                  color="success"
                  class="text-capitalize"
                >
                  View all featured themes
                </v-btn>
              </nuxt-link>
            </v-row>
          </v-card>
        </v-card>
      </v-col>
      <v-col cols="12" sm="8" md="8">
        <v-row>
          <v-col cols="12" sm="6" md="6">
            <v-card flat class="mx-auto pb-2" width="100%">
              <div class="mb-2">
                <img
                  src="https://themeforest.img.customer.envatousercontent.com/files/355260316/preview-sale-49.__large_preview.jpg?auto=compress%2Cformat&amp;q=80&amp;fit=crop&amp;crop=top&amp;max-h=8000&amp;max-w=590&amp;s=de0fe90f93b58d850993fad5ec687cf7"
                  alt="WordPress Themes"
                  loading="lazy"
                  width="100%"
                  height="90%"
                  class="d-block"
                />
              </div>
              <v-card flat>
                <h4>
                  <nuxt-link
                    to="#"
                    class="text-decoration-none black--text ml-3"
                    >Necromancers - eSports & Gaming Team WordPress
                    Theme</nuxt-link
                  >
                </h4>
                <nuxt-link to="#" class="text-decoration-none">
                  <h5 class="text--secondary ml-3 mb-3">
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

                    <h5 class="text--secondary pb-3">31 Sales</h5>
                  </v-card>
                  <v-card class="px-5" flat tile dense>
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
          <v-col cols="12" sm="6" md="6">
            <v-card flat class="mx-auto pb-2" width="100%">
              <div class="mb-2">
                <img
                  src="https://themeforest.img.customer.envatousercontent.com/files/354716794/01_texap_preview_large.__large_preview.jpg?auto=compress%2Cformat&amp;q=80&amp;fit=crop&amp;crop=top&amp;max-h=8000&amp;max-w=590&amp;s=27d6f0dd7177c1a86896d28d1ba6792d"
                  alt="WordPress Themes"
                  loading="lazy"
                  width="100%"
                  height="90%"
                  class="d-block"
                />
              </div>
              <v-card flat>
                <h4>
                  <nuxt-link
                    to="#"
                    class="text-decoration-none black--text ml-3"
                    >Necromancers - eSports & Gaming Team WordPress
                    Theme</nuxt-link
                  >
                </h4>
                <nuxt-link to="#" class="text-decoration-none">
                  <h5 class="text--secondary ml-3 mb-3">
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

                    <h5 class="text--secondary pb-3">31 Sales</h5>
                  </v-card>
                  <v-card class="px-5" flat tile dense>
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
          <v-col cols="12" sm="6" md="6">
            <v-card flat class="mx-auto pb-2" width="100%">
              <div class="mb-2">
                <img
                  src="https://themeforest.img.customer.envatousercontent.com/files/354752137/preview.__large_preview.jpg?auto=compress%2Cformat&amp;q=80&amp;fit=crop&amp;crop=top&amp;max-h=8000&amp;max-w=590&amp;s=484fa8485cdba8ba4a270000bb6445e6"
                  alt="WordPress Themes"
                  loading="lazy"
                  width="100%"
                  height="90%"
                  class="d-block"
                />
              </div>
              <v-card flat>
                <h4>
                  <nuxt-link
                    to="#"
                    class="text-decoration-none black--text ml-3"
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

                    <h5 class="text--secondary pb-3">31 Sales</h5>
                  </v-card>
                  <v-card class="px-5" flat tile dense>
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
          <v-col cols="12" sm="6" md="6">
            <v-card flat class="mx-auto pb-2" width="100%">
              <div class="mb-2">
                <img
                  src="https://themeforest.img.customer.envatousercontent.com/files/338448069/preview/preview-wp.__large_preview.jpg?auto=compress%2Cformat&amp;q=80&amp;fit=crop&amp;crop=top&amp;max-h=8000&amp;max-w=590&amp;s=e5c33287dc3ffa6dd7e603e143cf43df"
                  alt="WordPress Themes"
                  loading="lazy"
                  width="100%"
                  height="90%"
                  class="d-block"
                />
              </div>
              <v-card flat>
                <h4>
                  <nuxt-link
                    to="#"
                    class="text-decoration-none black--text ml-3"
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

                    <h5 class="text--secondary pb-3">31 Sales</h5>
                  </v-card>
                  <v-card class="px-5" flat tile dense>
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
      </v-col>
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