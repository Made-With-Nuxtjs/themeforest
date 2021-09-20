<template>
  <v-container>
    <IndividualSubHeader />
    <IndividualBreadcrumbReview />
    <v-row no-gutters class="mt-n5 ml-3">
      <v-col md="10" offset-md="1" class="pl-5">
        <h1 class="text--primary">
          Reviews for Kalles - Clean, Versatile, Responsive Shopify Theme - RTL
          support
        </h1>

        <v-row no-gutters>
          <v-col cols="12" sm="12" md="5">
            <v-card-actions>
              <span>
                By
                <nuxt-link to="#" class="text-decoration-none"
                  >The4</nuxt-link
                ></span
              >
              <v-rating
                v-model="rating"
                background-color="yellow"
                color="yellow accent-4"
                dense
                half-increments
                hover
                size="18"
                class="ml-5"
              ></v-rating>
              <span class="grey--text text-caption mr-2">
                {{ rating }}
              </span>
              <span class="text-caption mr-2">
                <nuxt-link to="#" class="text-decoration-none"
                  >(580 ratings)</nuxt-link
                >
              </span>
              <span class="text-caption mr-1 ml-3">
                <v-icon class="blue--text">mdi-chat</v-icon>
              </span>
              <span class="blue--text">
                <nuxt-link to="#" class="text-decoration-none"
                  >475 Comments</nuxt-link
                ></span
              >
            </v-card-actions>
          </v-col>
          <v-col cols="12" sm="12" md="7">
            <v-card-actions>
              <span class="text-caption mr-1 ml-n2">
                <v-icon size="18">mdi-cart</v-icon>
              </span>
              <span class="grey--text mr-3"> 5000 Sales </span>
              <span class="green--text">
                Recently Updated
                <v-icon class="green--text" size="18"
                  >mdi-check-circle</v-icon
                ></span
              >
              <span class="green--text ml-3">
                Well Documented
                <v-icon class="green--text" size="18"
                  >mdi-check-circle</v-icon
                ></span
              >
            </v-card-actions>
          </v-col>
        </v-row>

        <v-card flat class="grey lighten-4">
          <v-tabs align-with-title>
            <v-tabs-slider></v-tabs-slider>
            <v-tab class="text-capitalize text-caption"
              ><nuxt-link
                to="/individualPage"
                class="text-decoration-none text--secondary"
                >Item Details</nuxt-link
              ></v-tab
            >
            <v-tab class="text-capitalize text-caption">
              <nuxt-link
                to="/individualReview"
                class="text-decoration-none text--secondary"
                >Reviews</nuxt-link
              >
            </v-tab>
            <v-tab class="text-capitalize text-caption">
              <nuxt-link
                to="/individualComments"
                class="text-decoration-none text--secondary"
                >Comments</nuxt-link
              >
            </v-tab>
            <v-tab class="text-capitalize text-caption">
              <nuxt-link
                to="/individualSupports"
                class="text-decoration-none text--secondary"
                >Supports</nuxt-link
              >
            </v-tab>
          </v-tabs>

          <v-card flat>
            <!-- item Review -->
            <v-row no-gutters>
              <v-col cols="12" sm="6" md="8" class="class=" ml-16>
                <v-card flat class="pa-2" tile width="720px">
                  <v-row>
                    <v-col cols="8">
                      <v-card-actions>
                        <span class="subtitle-1 font-weight-bold">
                          581 Reviews</span
                        >
                        <v-rating
                          v-model="rating"
                          background-color="yellow"
                          color="yellow accent-4"
                          dense
                          hover
                          size="22"
                          class="ml-5"
                        ></v-rating>
                      </v-card-actions>
                    </v-col>

                    <v-col class="d-flex" cols="12" sm="4" md="4">
                      <v-select
                        v-model="select"
                        :items="items"
                        item-text="state"
                        return-object
                      ></v-select>
                    </v-col>
                  </v-row>
                </v-card>

                <v-card class="pa-2" tile width="720px">
                  <v-row width="720px">
                    <v-col cols="6">
                      <v-card-actions class="ma-0 pa-0">
                        <v-rating
                          v-model="rating"
                          background-color="yellow"
                          color="yellow accent-4"
                          dense
                          hover
                          size="22"
                          class="ml-5"
                        ></v-rating>
                        <span class="subtitle-1 font-weight-bold">
                          <span class="text--disabled">for</span> Design
                          Quality</span
                        >
                      </v-card-actions>
                    </v-col>
                    <v-col cols="6" class="">
                      <v-card-actions class="float-right ma-0 pa-0 mr-3">
                        <span class="text--primary mr-2">By</span
                        ><span>
                          <nuxt-link
                            to="#"
                            class="text-decoration-none text-caption mr-2"
                            >bluefcy1531</nuxt-link
                          ></span
                        >

                        <span class="text--disabled text-caption"
                          >16 Hours ago</span
                        >
                      </v-card-actions>
                    </v-col>
                  </v-row>
                  <v-divider />
                  <p class="mx-5 my-3">
                    real nice theme,i love it and we team love it,we do the
                    shopify tutorial by using kalles theme,and now we wanna
                    build our own brand using it again.
                  </p>
                </v-card>
                <v-card class="pa-2 mt-5" tile width="720px">
                  <v-row width="720px">
                    <v-col cols="6">
                      <v-card-actions class="ma-0 pa-0">
                        <v-rating
                          v-model="rating"
                          background-color="yellow"
                          color="yellow accent-4"
                          dense
                          hover
                          size="22"
                          class="ml-5"
                        ></v-rating>
                        <span class="subtitle-1 font-weight-bold">
                          <span class="text--disabled">for</span>
                          Feature Availability</span
                        >
                      </v-card-actions>
                    </v-col>
                    <v-col cols="6" class="">
                      <v-card-actions class="float-right ma-0 pa-0 mr-3">
                        <span class="text--primary mr-2">By</span
                        ><span>
                          <nuxt-link
                            to="#"
                            class="text-decoration-none text-caption mr-2"
                            >hapham88</nuxt-link
                          ></span
                        >

                        <span class="text--disabled text-caption"
                          >16 Hours ago</span
                        >
                      </v-card-actions>
                    </v-col>
                  </v-row>
                  <v-divider />
                  <p class="mx-5 my-3">
                    real nice theme,i love it and we team love it,we do the
                    shopify tutorial by using kalles theme,and now we wanna
                    build our own brand using it again.
                  </p>
                </v-card>
                <v-card class="pa-2 mt-5" tile width="720px">
                  <v-row width="720px">
                    <v-col cols="6">
                      <v-card-actions class="ma-0 pa-0">
                        <v-rating
                          v-model="rating"
                          background-color="yellow"
                          color="yellow accent-4"
                          dense
                          hover
                          size="22"
                          class="ml-5"
                        ></v-rating>
                        <span class="subtitle-1 font-weight-bold">
                          <span class="text--disabled">for</span>Customer
                          Support</span
                        >
                      </v-card-actions>
                    </v-col>
                    <v-col cols="6" class="">
                      <v-card-actions class="float-right ma-0 pa-0 mr-3">
                        <span class="text--primary mr-2">By</span
                        ><span>
                          <nuxt-link
                            to="#"
                            class="text-decoration-none text-caption mr-2"
                            >playwhatever_online</nuxt-link
                          ></span
                        >

                        <span class="text--disabled text-caption"
                          >5 days ago</span
                        >
                      </v-card-actions>
                    </v-col>
                  </v-row>
                  <v-divider />
                  <p class="mx-5 my-3">
                    The theme is nice, and the customer support team is even
                    better to help you resolve any issues in good timeframe.
                    Would recommend for any ecommerce store from beginning
                    entrepreneurs to experienced.
                  </p>
                </v-card>
                <v-card class="pa-2 mt-5" tile width="720px">
                  <v-row width="720px">
                    <v-col cols="6">
                      <v-card-actions class="ma-0 pa-0">
                        <v-rating
                          v-model="rating"
                          background-color="yellow"
                          color="yellow accent-4"
                          dense
                          hover
                          size="22"
                          class="ml-5"
                        ></v-rating>
                        <span class="subtitle-1 font-weight-bold">
                          <span class="text--disabled">for</span
                          >Flexibility</span
                        >
                      </v-card-actions>
                    </v-col>
                    <v-col cols="6" class="">
                      <v-card-actions class="float-right ma-0 pa-0 mr-3">
                        <span class="text--primary mr-2">By</span
                        ><span>
                          <nuxt-link
                            to="#"
                            class="text-decoration-none text-caption mr-2"
                            >omarnmk</nuxt-link
                          ></span
                        >

                        <span class="text--disabled text-caption">
                          9 days ago</span
                        >
                      </v-card-actions>
                    </v-col>
                  </v-row>
                  <v-divider />
                  <p class="mx-5 my-3">
                    Really great theme to use. Can customise every single part
                    of it. Really happy with my purchase :)
                  </p>
                </v-card>
                <v-card class="pa-2" tile width="720px">
                  <v-row width="720px">
                    <v-col cols="6">
                      <v-card-actions class="ma-0 pa-0">
                        <v-rating
                          v-model="rating"
                          background-color="yellow"
                          color="yellow accent-4"
                          dense
                          hover
                          size="22"
                          class="ml-5"
                        ></v-rating>
                        <span class="subtitle-1 font-weight-bold">
                          <span class="text--disabled">for</span> Design
                          Quality</span
                        >
                      </v-card-actions>
                    </v-col>
                    <v-col cols="6" class="">
                      <v-card-actions class="float-right ma-0 pa-0 mr-3">
                        <span class="text--primary mr-2">By</span
                        ><span>
                          <nuxt-link
                            to="#"
                            class="text-decoration-none text-caption mr-2"
                            >bluefcy1531</nuxt-link
                          ></span
                        >

                        <span class="text--disabled text-caption"
                          >16 Hours ago</span
                        >
                      </v-card-actions>
                    </v-col>
                  </v-row>
                  <v-divider />
                  <p class="mx-5 my-3">
                    real nice theme,i love it and we team love it,we do the
                    shopify tutorial by using kalles theme,and now we wanna
                    build our own brand using it again.
                  </p>
                </v-card>
                <v-card class="pa-2 mt-5" tile width="720px">
                  <v-row width="720px">
                    <v-col cols="6">
                      <v-card-actions class="ma-0 pa-0">
                        <v-rating
                          v-model="rating"
                          background-color="yellow"
                          color="yellow accent-4"
                          dense
                          hover
                          size="22"
                          class="ml-5"
                        ></v-rating>
                        <span class="subtitle-1 font-weight-bold">
                          <span class="text--disabled">for</span>
                          Feature Availability</span
                        >
                      </v-card-actions>
                    </v-col>
                    <v-col cols="6" class="">
                      <v-card-actions class="float-right ma-0 pa-0 mr-3">
                        <span class="text--primary mr-2">By</span
                        ><span>
                          <nuxt-link
                            to="#"
                            class="text-decoration-none text-caption mr-2"
                            >hapham88</nuxt-link
                          ></span
                        >

                        <span class="text--disabled text-caption"
                          >16 Hours ago</span
                        >
                      </v-card-actions>
                    </v-col>
                  </v-row>
                  <v-divider />
                  <p class="mx-5 my-3">
                    real nice theme,i love it and we team love it,we do the
                    shopify tutorial by using kalles theme,and now we wanna
                    build our own brand using it again.
                  </p>
                </v-card>
                <v-card class="pa-2 mt-5" tile width="720px">
                  <v-row width="720px">
                    <v-col cols="6">
                      <v-card-actions class="ma-0 pa-0">
                        <v-rating
                          v-model="rating"
                          background-color="yellow"
                          color="yellow accent-4"
                          dense
                          hover
                          size="22"
                          class="ml-5"
                        ></v-rating>
                        <span class="subtitle-1 font-weight-bold">
                          <span class="text--disabled">for</span>Customer
                          Support</span
                        >
                      </v-card-actions>
                    </v-col>
                    <v-col cols="6" class="">
                      <v-card-actions class="float-right ma-0 pa-0 mr-3">
                        <span class="text--primary mr-2">By</span
                        ><span>
                          <nuxt-link
                            to="#"
                            class="text-decoration-none text-caption mr-2"
                            >playwhatever_online</nuxt-link
                          ></span
                        >

                        <span class="text--disabled text-caption"
                          >5 days ago</span
                        >
                      </v-card-actions>
                    </v-col>
                  </v-row>
                  <v-divider />
                  <p class="mx-5 my-3">
                    The theme is nice, and the customer support team is even
                    better to help you resolve any issues in good timeframe.
                    Would recommend for any ecommerce store from beginning
                    entrepreneurs to experienced.
                  </p>
                </v-card>
                <v-card class="pa-2" tile width="720px">
                  <v-row width="720px">
                    <v-col cols="6">
                      <v-card-actions class="ma-0 pa-0">
                        <v-rating
                          v-model="rating"
                          background-color="yellow"
                          color="yellow accent-4"
                          dense
                          hover
                          size="22"
                          class="ml-5"
                        ></v-rating>
                        <span class="subtitle-1 font-weight-bold">
                          <span class="text--disabled">for</span> Design
                          Quality</span
                        >
                      </v-card-actions>
                    </v-col>
                    <v-col cols="6" class="">
                      <v-card-actions class="float-right ma-0 pa-0 mr-3">
                        <span class="text--primary mr-2">By</span
                        ><span>
                          <nuxt-link
                            to="#"
                            class="text-decoration-none text-caption mr-2"
                            >bluefcy1531</nuxt-link
                          ></span
                        >

                        <span class="text--disabled text-caption"
                          >16 Hours ago</span
                        >
                      </v-card-actions>
                    </v-col>
                  </v-row>
                  <v-divider />
                  <p class="mx-5 my-3">
                    real nice theme,i love it and we team love it,we do the
                    shopify tutorial by using kalles theme,and now we wanna
                    build our own brand using it again.
                  </p>
                </v-card>
                <v-card class="pa-2 mt-5" tile width="720px">
                  <v-row width="720px">
                    <v-col cols="6">
                      <v-card-actions class="ma-0 pa-0">
                        <v-rating
                          v-model="rating"
                          background-color="yellow"
                          color="yellow accent-4"
                          dense
                          hover
                          size="22"
                          class="ml-5"
                        ></v-rating>
                        <span class="subtitle-1 font-weight-bold">
                          <span class="text--disabled">for</span>
                          Feature Availability</span
                        >
                      </v-card-actions>
                    </v-col>
                    <v-col cols="6" class="">
                      <v-card-actions class="float-right ma-0 pa-0 mr-3">
                        <span class="text--primary mr-2">By</span
                        ><span>
                          <nuxt-link
                            to="#"
                            class="text-decoration-none text-caption mr-2"
                            >hapham88</nuxt-link
                          ></span
                        >

                        <span class="text--disabled text-caption"
                          >16 Hours ago</span
                        >
                      </v-card-actions>
                    </v-col>
                  </v-row>
                  <v-divider />
                  <p class="mx-5 my-3">
                    real nice theme,i love it and we team love it,we do the
                    shopify tutorial by using kalles theme,and now we wanna
                    build our own brand using it again.
                  </p>
                </v-card>
                <v-card class="pa-2 mt-5" tile width="720px">
                  <v-row width="720px">
                    <v-col cols="6">
                      <v-card-actions class="ma-0 pa-0">
                        <v-rating
                          v-model="rating"
                          background-color="yellow"
                          color="yellow accent-4"
                          dense
                          hover
                          size="22"
                          class="ml-5"
                        ></v-rating>
                        <span class="subtitle-1 font-weight-bold">
                          <span class="text--disabled">for</span>Customer
                          Support</span
                        >
                      </v-card-actions>
                    </v-col>
                    <v-col cols="6" class="">
                      <v-card-actions class="float-right ma-0 pa-0 mr-3">
                        <span class="text--primary mr-2">By</span
                        ><span>
                          <nuxt-link
                            to="#"
                            class="text-decoration-none text-caption mr-2"
                            >playwhatever_online</nuxt-link
                          ></span
                        >

                        <span class="text--disabled text-caption"
                          >5 days ago</span
                        >
                      </v-card-actions>
                    </v-col>
                  </v-row>
                  <v-divider />
                  <p class="mx-5 my-3">
                    The theme is nice, and the customer support team is even
                    better to help you resolve any issues in good timeframe.
                    Would recommend for any ecommerce store from beginning
                    entrepreneurs to experienced.
                  </p>
                </v-card>
                <v-card class="pa-2 mt-5" tile width="720px">
                  <v-row width="720px">
                    <v-col cols="6">
                      <v-card-actions class="ma-0 pa-0">
                        <v-rating
                          v-model="rating"
                          background-color="yellow"
                          color="yellow accent-4"
                          dense
                          hover
                          size="22"
                          class="ml-5"
                        ></v-rating>
                        <span class="subtitle-1 font-weight-bold">
                          <span class="text--disabled">for</span
                          >Flexibility</span
                        >
                      </v-card-actions>
                    </v-col>
                    <v-col cols="6" class="">
                      <v-card-actions class="float-right ma-0 pa-0 mr-3">
                        <span class="text--primary mr-2">By</span
                        ><span>
                          <nuxt-link
                            to="#"
                            class="text-decoration-none text-caption mr-2"
                            >omarnmk</nuxt-link
                          ></span
                        >

                        <span class="text--disabled text-caption">
                          9 days ago</span
                        >
                      </v-card-actions>
                    </v-col>
                  </v-row>
                  <v-divider />
                  <p class="mx-5 my-3">
                    Really great theme to use. Can customise every single part
                    of it. Really happy with my purchase :)
                  </p>
                </v-card>
              </v-col>

              <v-col cols="6" md="4">
                <v-card class="mx-auto mr-16 pa-7" max-width="344">
                  <div class="d-inline">
                    <v-menu offset-y>
                      <template #activator="{ on, attrs }">
                        <v-btn
                          color="primary"
                          dark
                          v-bind="attrs"
                          class="text-capitalize"
                          v-on="on"
                        >
                          Regular License
                          <v-icon size="15" class="ml-2"
                            >mdi-arrow-down-drop-circle-outline</v-icon
                          >
                        </v-btn>
                      </template>
                      <v-list>
                        <v-card flat max-width="300">
                          <p class="pl-5 d-inline">
                            Regular Lience
                            <v-btn class="primary" x-small>selected</v-btn>
                          </p>
                          <h4 class="d-inline float-right mr-3">$89</h4>
                          <p class="pl-5 mt-3 text--secondary">
                            Use, by you or one client, in a single end product
                            which end users are not charged for. The total price
                            includes the item price and a buyer fee.
                          </p>
                        </v-card>
                        <v-divider class="mb-4"></v-divider>
                        <v-card flat max-width="300">
                          <p class="pl-5 d-inline">
                            Extended License
                            <v-btn class="primary" x-small>selected</v-btn>
                          </p>
                          <h4 class="d-inline float-right mr-3">$4750</h4>
                          <p class="pl-5 mt-3 text--secondary">
                            Use, by you or one client, in a single end product
                            which end users are not charged for. The total price
                            includes the item price and a buyer fee.
                          </p>
                        </v-card>
                      </v-list>
                    </v-menu>
                  </div>
                  <div class="d-inline">
                    <h3 class="float-right">$89</h3>
                  </div>
                  <v-card flat class="mt-3">
                    <div class="d-inline">
                      <v-icon size="18">mdi-check</v-icon>
                    </div>
                    <div class="d-inline text-caption">
                      Quality checked by Envato
                    </div>
                  </v-card>
                  <v-card flat>
                    <div class="d-inline">
                      <v-icon size="18">mdi-check</v-icon>
                    </div>
                    <div class="d-inline text-caption">
                      Included:Future updates
                    </div>
                  </v-card>
                  <v-card flat>
                    <div class="d-inline">
                      <v-icon size="18">mdi-check</v-icon>
                    </div>
                    <div class="d-inline text-caption">
                      Included:6 months support from The4
                    </div>
                  </v-card>
                  <v-card flat>
                    <div class="d-inline">
                      <v-icon size="18">mdi-check</v-icon>
                    </div>
                    <div class="d-inline text-caption">
                      Extend support to 12 months
                    </div>
                    <h6
                      class="
                        d-inline
                        text-decoration-line-through text-capition
                      "
                    >
                      $3500
                    </h6>
                    <h5 class="d-inline pl-1">$1500</h5>
                  </v-card>

                  <p class="font-italic text-caption my-3 ml-5">
                    Price is in US dollars and excludes tax
                  </p>
                  <v-btn class="success text-capitalize" block
                    ><v-icon size="18" class="pr-4">mdi-cart</v-icon> Add To
                    cart</v-btn
                  >
                </v-card>

                <v-card class="mt-6" max-width="330">
                  <v-row class="ml-5">
                    <v-avatar class="my-4 ml-2">
                      <img
                        src="https://public-assets.envato-static.com/assets/badges/power_elite-230a9ec5e29940c34cf6f9f041430fd3a5edb22ac5927d0148ae2b99258a33ec.svg"
                      />
                    </v-avatar>

                    <p class="mt-7 ml-3">Power Elite Author</p>
                  </v-row>
                </v-card>

                <v-card class="mt-6 pa-6" max-width="330" height="auto">
                  <v-row>
                    <v-col cols="4">
                      <img
                        src="https://s3.envato.com/files/265668596/logo80png.png"
                        width="80"
                        height="80"
                        alt="The4"
                      />
                    </v-col>
                    <v-col cols="8">
                      <h2 class="mb-3">The4</h2>
                      <img
                        width="30"
                        height="30"
                        src="https://public-assets.envato-static.com/assets/badges/one_billion_milestone-s-6bafd9c1c66e21701fa25158e42e4f28a3ca101552f952c9680b10822f2c147e.svg"
                        alt="Milestone Member"
                        class="community-badges__badge--s"
                        title="Milestone Member: Part of the $1 billion community earnings milestone"
                      />
                      <img
                        width="30"
                        height="30"
                        src="https://public-assets.envato-static.com/assets/badges/power_elite-s-f2e0c6ae5b4e6b535a82594b1df540c31ac15d91a4d62ac66de507f2c0da98a1.svg"
                      />
                      <img
                        width="30"
                        height="30"
                        src="https://public-assets.envato-static.com/assets/badges/author_level_12-s-8ceeb5716185d8ef9da7dfce5f556ff0ad2eea64fa9a7120d23c5805649d26bd.svg"
                      />
                      <img
                        width="30"
                        height="30"
                        src="https://public-assets.envato-static.com/assets/badges/author_level_12-s-8ceeb5716185d8ef9da7dfce5f556ff0ad2eea64fa9a7120d23c5805649d26bd.svg"
                      />
                      <img
                        width="30"
                        height="30"
                        src="https://public-assets.envato-static.com/assets/badges/industrious_inventor-s-d5edf7b13457a553020719e90577d619879e1d6108651fa99da27a3b246c396e.svg"
                        alt="Industrious Inventor"
                        class="community-badges__badge--s"
                        title="Industrious Inventor: Created a helpful tool/app for Envato Market users"
                      />

                      <img
                        width="30"
                        height="30"
                        src="https://public-assets.envato-static.com/assets/badges/had_trending_item-s-df25504354e95350eb7eaa475e4d6fe77cb972b4a0b225358eac6b99e6acc415.svg"
                        alt="Trendsetter"
                        class="community-badges__badge--s"
                        title="Trendsetter: Had an item that was trending"
                      />
                      <img
                        width="30"
                        height="30"
                        src="https://public-assets.envato-static.com/assets/badges/feedback_guru-s-6355c624b77e0d4e416fd234249468786178e1f6117ce804e56c9a6f02b2a170.svg"
                        alt="Feedback Guru"
                        class="community-badges__badge--s"
                        title="Feedback Guru: Participated in a focus group or interview to improve the user experience on Envato Market"
                      />
                      <img
                        width="30"
                        height="30"
                        src="https://public-assets.envato-static.com/assets/badges/attended_community_meetup-s-4419b0cc225cfd92c4f9e9eff69c885aceddbdd3e24d5403ba4b7f84a17973fd.svg"
                        alt="Meetup Participant"
                        class="community-badges__badge--s"
                        title="Meetup Participant: Attended one of our Meetups around the world"
                      />

                      <img
                        width="30"
                        height="30"
                        src="https://public-assets.envato-static.com/assets/badges/mo_bro-s-92f29baf20edc3e451c7c8a7730a9ad9f38055be34ff38106d7c70070a7ae2d3.svg"
                        alt="Mo Bro"
                        class="community-badges__badge--s"
                        title="Mo Bro: Pulled off some great moustache to raise money or awareness for Movember Australia"
                      />

                      <img
                        width="30"
                        height="30"
                        src="https://public-assets.envato-static.com/assets/badges/one_billion_milestone-s-6bafd9c1c66e21701fa25158e42e4f28a3ca101552f952c9680b10822f2c147e.svg"
                        alt="Milestone Member"
                        class="community-badges__badge--s"
                        title="Milestone Member: Part of the $1 billion community earnings milestone"
                      />
                      <img
                        width="30"
                        height="30"
                        src="https://public-assets.envato-static.com/assets/badges/one_billion_milestone-s-6bafd9c1c66e21701fa25158e42e4f28a3ca101552f952c9680b10822f2c147e.svg"
                        alt="Milestone Member"
                        class="community-badges__badge--s"
                        title="Milestone Member: Part of the $1 billion community earnings milestone"
                      />
                      <img
                        width="30"
                        height="30"
                        src="https://public-assets.envato-static.com/assets/badges/one_billion_milestone-s-6bafd9c1c66e21701fa25158e42e4f28a3ca101552f952c9680b10822f2c147e.svg"
                        alt="Milestone Member"
                        class="community-badges__badge--s"
                        title="Milestone Member: Part of the $1 billion community earnings milestone"
                      />
                      <img
                        width="30"
                        height="30"
                        src="https://public-assets.envato-static.com/assets/badges/one_billion_milestone-s-6bafd9c1c66e21701fa25158e42e4f28a3ca101552f952c9680b10822f2c147e.svg"
                        alt="Milestone Member"
                        class="community-badges__badge--s"
                        title="Milestone Member: Part of the $1 billion community earnings milestone"
                      />
                      <img
                        width="30"
                        height="30"
                        src="https://public-assets.envato-static.com/assets/badges/one_billion_milestone-s-6bafd9c1c66e21701fa25158e42e4f28a3ca101552f952c9680b10822f2c147e.svg"
                        alt="Milestone Member"
                        class="community-badges__badge--s"
                        title="Milestone Member: Part of the $1 billion community earnings milestone"
                      />
                      <img
                        width="30"
                        height="30"
                        src="https://public-assets.envato-static.com/assets/badges/one_billion_milestone-s-6bafd9c1c66e21701fa25158e42e4f28a3ca101552f952c9680b10822f2c147e.svg"
                        alt="Milestone Member"
                        class="community-badges__badge--s"
                        title="Milestone Member: Part of the $1 billion community earnings milestone"
                      />
                    </v-col>

                    <v-btn class="grey lighten-3" small block>
                      <nuxt-link
                        to="#"
                        class="text-decoration-none text-capitalize"
                      >
                        View protfolio
                      </nuxt-link></v-btn
                    >
                  </v-row>
                </v-card>

                <v-card class="mt-6 pa-6" max-width="330">
                  <v-row>
                    <v-col cols="5">
                      <h5 class="pa-1">Last Update</h5>
                      <h5 class="pa-1">Published</h5>
                      <h5 class="pa-1">High Resolution</h5>
                      <h5 class="pa-1">Compatible Browsers</h5>
                      <h5 class="pa-1">Compatible With</h5>
                      <h5 class="pa-1">Software Version</h5>
                      <h5 class="pa-1">ThemeForest Files Included</h5>
                      <h5 class="pa-1">Columns</h5>
                      <h5 class="pa-1">Documentation</h5>
                      <h5 class="pa-1">Layout</h5>
                      <h5 class="pa-1">Tags</h5>
                    </v-col>
                    <v-col cols="7">
                      <h5 class="text-caption pa-1">9 September 21</h5>
                      <h5 class="text-caption pa-1">9 April 20</h5>
                      <h5 class="text-caption pa-1">
                        <nuxt-link to="#" class="text-decoration-none"
                          >Yes</nuxt-link
                        >
                      </h5>
                      <h5 class="text-caption pa-1">
                        <nuxt-link to="#" class="text-decoration-none"
                          >Firefox</nuxt-link
                        >,
                        <nuxt-link to="#" class="text-decoration-none"
                          >Safari</nuxt-link
                        >,
                        <nuxt-link to="#" class="text-decoration-none"
                          >Opera</nuxt-link
                        >,
                        <nuxt-link to="#" class="text-decoration-none"
                          >Chrome</nuxt-link
                        >,
                        <nuxt-link to="#" class="text-decoration-none"
                          >Edge</nuxt-link
                        >
                      </h5>
                      <h5 class="text-caption pa-1">
                        <nuxt-link to="#" class="text-decoration-none"
                          >Bootstrap 4.x</nuxt-link
                        >,
                      </h5>
                      <h5 class="text-caption pa-1">
                        <nuxt-link to="#" class="text-decoration-none"
                          >Shopify 2.0</nuxt-link
                        >
                      </h5>
                      <h5 class="text-caption pa-1">
                        <nuxt-link to="#" class="text-decoration-none"
                          >JS Files</nuxt-link
                        >, <nuxt-link to="#">Edge</nuxt-link>
                      </h5>
                      <h5 class="text-caption pa-1">
                        <nuxt-link to="#" class="text-decoration-none"
                          >2</nuxt-link
                        >,
                      </h5>
                      <h5 class="text-caption pa-1">
                        <nuxt-link to="#" class="text-decoration-none"
                          >Well Documented
                        </nuxt-link>
                      </h5>
                      <h5 class="text-caption pa-1">
                        <nuxt-link to="#" class="text-decoration-none"
                          >Responsive</nuxt-link
                        >
                      </h5>
                      <h5 class="text-caption pa-1">
                        <nuxt-link to="#" class="text-decoration-none">
                          color swatches, dropshipping, electronics, fashion
                          template, handmade, jewelry shopify theme, online
                          fashion store, pod business, responisve shopify theme,
                          right to left, RTL Arabic, shopify section, single
                          product shopify theme, the best shopify
                          theme</nuxt-link
                        >
                      </h5>
                    </v-col>
                  </v-row>
                </v-card>
                <v-card flat class="text-center ma-4">
                  <h6>© All Rights Reserved The4</h6>
                  <h6>
                    <nuxt-link to="#" class="text-decoration-none"
                      >Contact the Envato Market Help Team</nuxt-link
                    >
                  </h6>
                </v-card>
              </v-col>
            </v-row>
            <!-- ---pagination -->
            <div class="text-center">
              <v-pagination v-model="page" :length="6"></v-pagination>
            </div>
          </v-card>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>
<script>
export default {
  data() {
    return {
      select: { state: 'Sort by Newest' },
      items: [
        { state: 'Sort by Newest' },
        { state: 'Sort by Highest Rating' },
        { state: 'Sort by Lowest Rating' },
      ],
    }
  },
}
</script>
