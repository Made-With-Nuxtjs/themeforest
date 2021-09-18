<template>
  <v-container>
    <v-row class="mt-16 pt-13">
      <v-col cols="12" sm="6" md="6">
        <v-card
          class="d-flex align-center grey lighten-5 mb-4"
          flat
          height="100%"
          tile
        >
          <v-card flat tile>
            <h1 class="ml-16 pa-7 text--secondary">
              Browse this week's best selling WordPress themes
            </h1>
            <h3 class="ml-16 pl-7 text--disabled">
              This week's best web themes & templates have arrived.
            </h3>
            <v-row class="mx-10 pl-13 mt-8">
              <nuxt-link to="" class="text-decoration-none">
                <v-btn
                  elevation="10"
                  tile
                  color="success"
                  class="text-capitalize"
                >
                  View more bestsellers
                </v-btn>
              </nuxt-link>
            </v-row>
          </v-card>
        </v-card>
      </v-col>
      <v-col cols="12" sm="6" md="6">
        <v-row>
          <v-col cols="12" sm="6" md="6">
            <v-card flat class="mx-auto pb-2" width="100%">
              <div class="mb-2">
                <img
                  src="https://themeforest.img.customer.envatousercontent.com/files/354926309/screenshots/00-Preview.__large_preview.jpg?auto=compress%2Cformat&amp;q=80&amp;fit=crop&amp;crop=top&amp;max-h=8000&amp;max-w=590&amp;s=8c509c595e1fbc408fb80a59e61a1e51"
                  alt="WordPress Themes"
                  loading="lazy"
                  width="100%"
                  height="90%"
                  class="d-block"
                />
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

                    <h5 class="text--secondary pb-1">31 Sales</h5>
                  </v-card>
                  <v-card class="px-4" flat tile dense>
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
                  src="https://themeforest.img.customer.envatousercontent.com/files/314864885/Cover%20(6).__large_preview.jpg?auto=compress%2Cformat&amp;q=80&amp;fit=crop&amp;crop=top&amp;max-h=8000&amp;max-w=590&amp;s=c10b9825db9eb0d2d0fedefba0972fc8"
                  alt="WordPress Themes"
                  loading="lazy"
                  width="100%"
                  height="90%"
                  class="d-block"
                />
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

                    <h5 class="text--secondary pb-1">31 Sales</h5>
                  </v-card>
                  <v-card class="px-4" flat tile dense>
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
                  src="https://themeforest.img.customer.envatousercontent.com/files/346014871/preview_26.06.21.__large_preview.png?auto=compress%2Cformat&amp;q=80&amp;fit=crop&amp;crop=top&amp;max-h=8000&amp;max-w=590&amp;s=e2f0b91c02a8d779ce95a58434a60d15"
                  alt="WordPress Themes"
                  loading="lazy"
                  width="100%"
                  height="90%"
                  class="d-block"
                />
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

                    <h5 class="text--secondary pb-1">31 Sales</h5>
                  </v-card>
                  <v-card class="px-4" flat tile dense>
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
                  src="https://themeforest.img.customer.envatousercontent.com/files/355350313/01_betheme.__large_preview.png?auto=compress%2Cformat&amp;q=80&amp;fit=crop&amp;crop=top&amp;max-h=8000&amp;max-w=590&amp;s=6801408d33ff6086682d3972e980e10f"
                  alt="WordPress Themes"
                  loading="lazy"
                  width="100%"
                  height="90%"
                  class="d-block"
                />
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

                    <h5 class="text--secondary pb-1">31 Sales</h5>
                  </v-card>
                  <v-card class="px-4" flat tile dense>
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


