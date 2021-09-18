<template>
  <v-container>
    <v-row class="">
      <v-row class="text-center justify-center">
        <h1 class="font-weight-light">
          Check out our newest themes and templates.
        </h1>
        <p class="text--secondary my-6">
          We carefully review new entries from our community one by one to make
          sure they meet high-quality design and functionality standards. From
          multipurpose themes to niche templates, you’ll always find something
          that catches your eye.
        </p>
      </v-row>
      <v-row align="center" justify="center">
        <v-col cols="2">
          <nuxt-link to="#" class="text-decoration-none ma-3">
            <v-btn class="px-7"> All Categories </v-btn></nuxt-link
          ></v-col
        >
        <v-col cols="2">
          <nuxt-link to="#" class="text-decoration-none ma-3">
            <v-btn class="px-7"> Site Tempaltes </v-btn></nuxt-link
          ></v-col
        >
        <v-col cols="2">
          <nuxt-link to="#" class="text-decoration-none ma-3">
            <v-btn class="px-11"> Wordpress </v-btn></nuxt-link
          ></v-col
        >
        <v-col cols="2">
          <nuxt-link to="#" class="text-decoration-none ma-3">
            <v-btn class="px-10"> CMS Themes </v-btn></nuxt-link
          ></v-col
        >
        <v-col cols="2">
          <nuxt-link to="#" class="text-decoration-none ma-3">
            <v-btn class="px-11"> eCommerce </v-btn></nuxt-link
          ></v-col
        >
        <v-col cols="2">
          <nuxt-link to="#" class="text-decoration-none ma-3">
            <v-btn class="px-11"> Blogging </v-btn></nuxt-link
          ></v-col
        >
        <v-col cols="2">
          <nuxt-link to="#" class="text-decoration-none ma-3">
            <v-btn class="px-11"> Marketing </v-btn></nuxt-link
          ></v-col
        >
        <v-col cols="2">
          <nuxt-link to="#" class="text-decoration-none ma-3">
            <v-btn class="px-15"> Forums </v-btn></nuxt-link
          ></v-col
        >
        <v-col cols="2">
          <nuxt-link to="#" class="text-decoration-none ma-3">
            <v-btn class="px-7"> Muse Tempates </v-btn></nuxt-link
          ></v-col
        >
        <v-col cols="2">
          <nuxt-link to="#" class="text-decoration-none ma-3">
            <v-btn class=""> Staic Site Generators </v-btn></nuxt-link
          ></v-col
        >
        <v-col cols="2">
          <nuxt-link to="#" class="text-decoration-none ma-3">
            <v-btn class="px-16"> Course </v-btn></nuxt-link
          ></v-col
        >
        <v-col cols="2">
          <nuxt-link to="#" class="text-decoration-none ma-3">
            <v-btn class="px-8"> Temlate Kits </v-btn></nuxt-link
          ></v-col
        >
        <!-- <nuxt-link to="#" class="text-decoration-none  ma-3"> <v-btn class="px-8">  UI Templates </v-btn></nuxt-link> -->
      </v-row>
      <v-row>
        <v-col cols="6" sm="3" md="3">
          <v-card
            flat
            class="mx-auto pb-2"
            width="90%"
            height="90%"
            :elevation="17"
          >
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
              <h4 class="ml-3 truncate-overflow">
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

              <v-card class="d-flex justify-space-between" flat tile>
                <h3 class="ml-3 pt-2 text--secondary">$45</h3>

                <v-card class="px-4 pb-3" flat tile dense>
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
        <v-col cols="6" sm="3" md="3">
          <v-card
            flat
            class="mx-auto pb-2"
            width="90%"
            height="90%"
            :elevation="17"
          >
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
              <h4 class="ml-3 truncate-overflow">
                <nuxt-link to="#" class="text-decoration-none black--text">
                  Meety – Events & Meetups Elementor Template Kit
                </nuxt-link>
              </h4>
              <nuxt-link to="#" class="text-decoration-none">
                <h5 class="text--primary font-weight-light ml-3 mb-3">
                  by merkulove in Events Entertainment
                </h5>
              </nuxt-link>

              <v-card class="d-flex justify-space-between" flat tile>
                <h3 class="ml-3 pt-2 text--secondary">$24</h3>

                <v-card class="px-4 pb-3" flat tile dense>
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
        <v-col cols="6" sm="3" md="3">
          <v-card
            flat
            class="mx-auto pb-2"
            width="90%"
            height="90%"
            :elevation="17"
          >
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
              <h4 class="ml-3 truncate-overflow">
                <nuxt-link to="#" class="text-decoration-none black--text">
                  Always - Responsive Drupal 9 Wedding Theme
                </nuxt-link>
              </h4>
              <nuxt-link to="#" class="text-decoration-none">
                <h5 class="text--primary font-weight-light ml-3 mb-3">
                  by drupalet in Events
                </h5>
              </nuxt-link>

              <v-card class="d-flex justify-space-between" flat tile>
                <h3 class="ml-3 pt-2 text--secondary">$49</h3>

                <v-card class="px-4 pb-3" flat tile dense>
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
        <v-col cols="6" sm="3" md="3">
          <v-card
            flat
            class="mx-auto pb-2"
            width="90%"
            height="90%"
            :elevation="17"
          >
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
              <h4 class="ml-3 truncate-overflow">
                <nuxt-link to="#" class="text-decoration-none black--text">
                  Nusafe - Charity & Non-Profit Elementor Template Kit
                </nuxt-link>
              </h4>
              <nuxt-link to="#" class="text-decoration-none">
                <h5 class="text--primary font-weight-light ml-3 mb-3">
                  by themesflat in Non Profit Religion
                </h5>
              </nuxt-link>

              <v-card class="d-flex justify-space-between" flat tile>
                <h3 class="ml-3 pt-2 text--secondary">$30</h3>

                <v-card class="px-4 pb-3" flat tile dense>
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
        <v-col cols="6" sm="3" md="3">
          <v-card
            flat
            class="mx-auto pb-2"
            width="90%"
            height="90%"
            :elevation="17"
          >
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
              <h4 class="ml-3 truncate-overflow">
                <nuxt-link to="#" class="text-decoration-none black--text">
                  Mitako - Multipurpose HTML Template
                </nuxt-link>
              </h4>
              <nuxt-link to="#" class="text-decoration-none">
                <h5 class="text--primary font-weight-light ml-3 mb-3">
                  by XpressRow in Business
                </h5>
              </nuxt-link>

              <v-card class="d-flex justify-space-between" flat tile>
                <h3 class="ml-3 pt-2 text--secondary">$45</h3>

                <v-card class="px-4 pb-3" flat tile dense>
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
        <v-col cols="6" sm="3" md="3">
          <v-card
            flat
            class="mx-auto pb-2"
            width="90%"
            height="90%"
            :elevation="17"
          >
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
              <h4 class="ml-3 truncate-overflow">
                <nuxt-link to="#" class="text-decoration-none black--text">
                  Tecnic – Digital Marketing Hubspot Theme
                </nuxt-link>
              </h4>
              <nuxt-link to="#" class="text-decoration-none">
                <h5 class="text--primary font-weight-light ml-3 mb-3">
                  by YogsThemes in Technology
                </h5>
              </nuxt-link>

              <v-card class="d-flex justify-space-between" flat tile>
                <h3 class="ml-3 pt-2 text--secondary">$45</h3>

                <v-card class="px-4 pb-3" flat tile dense>
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
        <v-col cols="6" sm="3" md="3">
          <v-card
            flat
            class="mx-auto pb-2"
            width="90%"
            height="90%"
            :elevation="17"
          >
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
              <h4 class="ml-3 truncate-overflow">
                <nuxt-link to="#" class="text-decoration-none black--text"
                  >BeautyShop - Premium Responsive Bigcommerce Theme.
                </nuxt-link>
              </h4>
              <nuxt-link to="#" class="text-decoration-none">
                <h5 class="text--primary font-weight-light ml-3 mb-3">
                  by expandtheme in Bigcommerce
                </h5>
              </nuxt-link>

              <v-card class="d-flex justify-space-between" flat tile>
                <h3 class="ml-3 pt-2 text--secondary">$139</h3>

                <v-card class="px-4 pb-3" flat tile dense>
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
        <v-col cols="6" sm="3" md="3">
          <v-card
            flat
            class="mx-auto pb-2"
            width="90%"
            height="90%"
            :elevation="17"
          >
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
              <h4 class="ml-3 truncate-overflow">
                <nuxt-link to="#" class="text-decoration-none black--text">
                  HireCo - Recruitment Services React Template
                </nuxt-link>
              </h4>
              <nuxt-link to="#" class="text-decoration-none">
                <h5 class="text--primary font-weight-light ml-3 mb-3">
                  by dan_fisher in Entertainment
                </h5>
              </nuxt-link>

              <v-card class="d-flex justify-space-between" flat tile>
                <h3 class="ml-3 pt-2 text--secondary">$40</h3>

                <v-card class="px-4 pb-3" flat tile dense>
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
        <v-row align="center" justify="space-around" class="ma-10">
          <nuxt-link to="" class="text-decoration-none">
            <v-btn elevation="21" tile color="success" class="text-capitalize">
              View more new items
            </v-btn>
          </nuxt-link>
        </v-row>
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