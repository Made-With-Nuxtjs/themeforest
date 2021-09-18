<template>
  <v-container>
    <v-row class="my-16">
      <v-col cols="12" sm="6" md="6" class="pr-7">
        <h1>
          Professional WordPress Themes & Website Templates for any project
        </h1>
        <h4 class="subtitle-1 mb-12">
          Discover thousands of easy to customize themes, templates & CMS
          products, made by world-class developers.
        </h4>
        <v-card class="mx-auto" width="100%" height="70">
          <v-card-title>
            <v-text-field
              flat
              solo
              label="e.g. responsive Wordpress"
              append-icon="mdi-magnify"
              suffix="Search"
            ></v-text-field>
          </v-card-title>
        </v-card>
      </v-col>
      <v-col cols="12" sm="6" md="6" class="pl-7">
        <img
          src="https://assets.market-storefront.envato-static.com/storefront/packs/media/images/home/themeforest/search-header-e9b1f87ec2352b50a7d1b2da92ee268d.png"
          loading="eager"
          alt="ThemeForest: 43,354 WordPress Themes &amp; Website Templates From $3"
          width="100%"
          height="90%"
          class="home-hero_component__image"
        />
      </v-col>
    </v-row>
    <v-row class="my-16">
      <v-col cols="12" sm="4" md="4" class="pr-7">
        <v-hover v-slot="{ hover }" open-delay="20">
          <v-card
            flat
            class="mx-auto"
            width="100%"
            :elevation="hover ? 20 : 2"
            :class="{ 'on-hover': hover }"
            align="center"
          >
            <v-card flat class="pt-9 mb-16 pb-10">
              <h1>WordPress Themes</h1>
              <h4 class="subtitle-1">Thousands of WordPress themes</h4>
              <div>
                <nuxt-link to="#" class="d-inline pa-2 text-decoration-none">
                  Newest</nuxt-link
                >

                <nuxt-link to="#" class="d-inline pa-2 text-decoration-none">
                  Bestsellers</nuxt-link
                >
              </div>
            </v-card>
            <div>
              <v-fab-transition>
                <v-btn fab small absolute center class="pb-10 pr-15">
                  <img
                    alt="WordPress Themes"
                    width="65"
                    height="65"
                    src="https://assets.market-storefront.envato-static.com/storefront/packs/media/images/category-icons/themeforest/wordpress-38017feb3efbc9d223cfb8472fba3cb8.svg"
                    class="d-block"
                    absolute
                    center
                  />
                </v-btn>
              </v-fab-transition>
              <img
                src="https://assets.market-storefront.envato-static.com/storefront/packs/media/images/home/themeforest/category-tiles-wordpress-04e605078599969bc24c2b465b73d1a3.png"
                alt="WordPress Themes"
                loading="lazy"
                width="80%"
                height="90%"
                class="d-block"
              />
            </div>
          </v-card>
        </v-hover>
      </v-col>
      <v-col cols="12" sm="4" md="4" class="pr-7">
        <v-hover v-slot="{ hover }" open-delay="20">
          <v-card
            flat
            class="mx-auto"
            width="100%"
            :elevation="hover ? 20 : 2"
            :class="{ 'on-hover': hover }"
            align="center"
          >
            <v-card flat class="pt-9 mb-16 pb-10">
              <h1>eCommerce Templates</h1>
              <h4 class="subtitle-1">Beautiful website templates</h4>
              <div>
                <nuxt-link to="#" class="d-inline pa-2 text-decoration-none">
                  Newest</nuxt-link
                >

                <nuxt-link to="#" class="d-inline pa-2 text-decoration-none">
                  Bestsellers</nuxt-link
                >
              </div>
            </v-card>
            <div>
              <v-fab-transition>
                <v-btn fab small absolute center class="pb-10 pr-15">
                  <img
                    alt="WordPress Themes"
                    width="65"
                    height="65"
                    src="https://assets.market-storefront.envato-static.com/storefront/packs/media/images/category-icons/themeforest/ecommerce-6764e61d48ed9f67fcef55f6276819b8.svg"
                    class="d-block"
                    absolute
                    center
                  />
                </v-btn>
              </v-fab-transition>
              <img
                src="https://assets.market-storefront.envato-static.com/storefront/packs/media/images/home/themeforest/category-tiles-ecommerce-d069e8d98640114a13897ad7475202c8.png"
                alt="WordPress Themes"
                loading="lazy"
                width="80%"
                height="90%"
                class="d-block"
              />
            </div>
          </v-card>
        </v-hover>
      </v-col>
      <v-col cols="12" sm="4" md="4" class="pr-7">
        <v-hover v-slot="{ hover }" open-delay="20">
          <v-card
            flat
            class="mx-auto"
            width="100%"
            :elevation="hover ? 20 : 2"
            :class="{ 'on-hover': hover }"
            align="center"
          >
            <v-card flat class="pt-9 mb-16 pb-10">
              <h1>Site Templates</h1>
              <h4 class="subtitle-1">HTML and website templates</h4>
              <div>
                <nuxt-link to="#" class="d-inline pa-2 text-decoration-none">
                  Newest</nuxt-link
                >

                <nuxt-link to="#" class="d-inline pa-2 text-decoration-none">
                  Bestsellers</nuxt-link
                >
              </div>
            </v-card>
            <div>
              <v-fab-transition>
                <v-btn fab small absolute center class="pb-10 pr-15">
                  <img
                    alt="WordPress Themes"
                    width="65"
                    height="65"
                    src="https://assets.market-storefront.envato-static.com/storefront/packs/media/images/category-icons/themeforest/site-templates-4b524d1996efd02a14b8a78d6f827e04.svg"
                    class="d-block"
                    absolute
                    center
                  />
                </v-btn>
              </v-fab-transition>
              <img
                src="https://assets.market-storefront.envato-static.com/storefront/packs/media/images/home/themeforest/category-tiles-site-templates-e4da8eef2122e7d2c0178b1d5a63251f.png"
                alt="WordPress Themes"
                loading="lazy"
                width="80%"
                height="90%"
                class="d-block"
              />
            </div>
          </v-card>
        </v-hover>
      </v-col>
      <v-col cols="12" sm="4" md="4" class="pr-7">
        <v-hover v-slot="{ hover }" open-delay="20">
          <v-card
            flat
            class="mx-auto"
            width="100%"
            :elevation="hover ? 20 : 2"
            :class="{ 'on-hover': hover }"
            align="center"
          >
            <v-card flat class="pt-9 mb-16 pb-10">
              <h1>Marketing Templates</h1>
              <h4 class="subtitle-1">
                Email, newsletter and landing page templates.
              </h4>
              <div>
                <nuxt-link to="#" class="d-inline pa-2 text-decoration-none">
                  Newest</nuxt-link
                >

                <nuxt-link to="#" class="d-inline pa-2 text-decoration-none">
                  Bestsellers</nuxt-link
                >
              </div>
            </v-card>
            <div>
              <v-fab-transition>
                <v-btn fab small absolute center class="pb-10 pr-15">
                  <img
                    alt="WordPress Themes"
                    width="65"
                    height="65"
                    src="https://assets.market-storefront.envato-static.com/storefront/packs/media/images/category-icons/themeforest/marketing-bfe20e6450d91d1d92e89f512af5cfe8.svg"
                    class="d-block"
                    absolute
                    center
                  />
                </v-btn>
              </v-fab-transition>
              <img
                src="https://assets.market-storefront.envato-static.com/storefront/packs/media/images/home/themeforest/category-tiles-marketing-aa0c86ed0c48d27c47350a89b393268a.png"
                alt="WordPress Themes"
                loading="lazy"
                width="80%"
                height="90%"
                class="d-block"
              />
            </div>
          </v-card>
        </v-hover>
      </v-col>
      <v-col cols="12" sm="4" md="4" class="pr-7">
        <v-hover v-slot="{ hover }" open-delay="20">
          <v-card
            flat
            class="mx-auto"
            width="100%"
            :elevation="hover ? 20 : 2"
            :class="{ 'on-hover': hover }"
            align="center"
          >
            <v-card flat class="pt-9 mb-16 pb-10">
              <h1>CMS Templates</h1>
              <h4 class="subtitle-1">Over 1,700 CMS website templates</h4>
              <div>
                <nuxt-link to="#" class="d-inline pa-2 text-decoration-none">
                  Newest</nuxt-link
                >

                <nuxt-link to="#" class="d-inline pa-2 text-decoration-none">
                  Bestsellers</nuxt-link
                >
              </div>
            </v-card>
            <div>
              <v-fab-transition>
                <v-btn fab small absolute center class="pb-10 pr-15">
                  <img
                    alt="WordPress Themes"
                    width="65"
                    height="65"
                    src="https://assets.market-storefront.envato-static.com/storefront/packs/media/images/category-icons/themeforest/cms-themes-69e2462231b345dca78df22eee42c3d0.svg"
                    class="d-block"
                    absolute
                    center
                  />
                </v-btn>
              </v-fab-transition>
              <img
                src="https://assets.market-storefront.envato-static.com/storefront/packs/media/images/home/themeforest/category-tiles-cms-themes-dcf193e313c6cc9c0f9b26a394bb3283.png"
                alt="WordPress Themes"
                loading="lazy"
                width="80%"
                height="90%"
                class="d-block"
              />
            </div>
          </v-card>
        </v-hover>
      </v-col>
      <v-col cols="12" sm="4" md="4" class="pr-7">
        <v-hover v-slot="{ hover }" open-delay="20">
          <v-card
            flat
            class="mx-auto"
            width="100%"
            :elevation="hover ? 20 : 2"
            :class="{ 'on-hover': hover }"
            align="center"
          >
            <v-card flat class="pt-9 mb-16 pb-10">
              <h1>Blogging</h1>
              <h4 class="subtitle-1">Blogger templates and themes</h4>
              <div>
                <nuxt-link to="#" class="d-inline pa-2 text-decoration-none">
                  Newest</nuxt-link
                >

                <nuxt-link to="#" class="d-inline pa-2 text-decoration-none">
                  Bestsellers</nuxt-link
                >
              </div>
            </v-card>
            <div>
              <v-fab-transition>
                <v-btn fab small absolute center class="pb-10 pr-15">
                  <img
                    alt="WordPress Themes"
                    width="65"
                    height="65"
                    src="https://assets.market-storefront.envato-static.com/storefront/packs/media/images/category-icons/themeforest/blogging-96fbea50c1aa03e434845f5795e8aa2f.svg"
                    class="d-block"
                    absolute
                    center
                  />
                </v-btn>
              </v-fab-transition>
              <img
                src="https://assets.market-storefront.envato-static.com/storefront/packs/media/images/home/themeforest/category-tiles-blogging-a36c3a96508905ed8b77df66c9e8d4cf.png"
                alt="WordPress Themes"
                loading="lazy"
                width="80%"
                height="90%"
                class="d-block"
              />
            </div>
          </v-card>
        </v-hover>
      </v-col>
      <v-row align="center" justify="space-around" class="ma-10">
        <nuxt-link to="" class="text-decoration-none">
          <v-btn elevation="10" tile color="success" class="text-capitalize">
            View All Categories
          </v-btn>
        </nuxt-link>
      </v-row>
    </v-row>
    <v-row class="my-16">
      <v-col cols="12" sm="6" md="6">
        <v-row class="grey lighten-5">
          <v-col cols="6" sm="6" md="6">
            <v-hover v-slot="{ hover }">
              <v-card class="mx-auto" color="grey lighten-4" max-width="600">
                <v-img
                  :aspect-ratio="17 / 8"
                  src="https://themeforest.img.customer.envatousercontent.com/files/355123468/Preview_big30.png?auto=compress%2Cformat&amp;fit=crop&amp;crop=top&amp;w=590&amp;h=300&amp;s=fa8bf9b578df3051b45153e2d0857177"
                >
                  <v-expand-transition>
                    <div
                      v-if="hover"
                      class="
                        d-flex
                        transition-fast-in-fast-out
                        white
                        darken-2
                        v-card--reveal
                      "
                      style="height: 40%"
                    >
                      <div>
                        <div class="d-block">
                          <nuxt-link to="#" class="text-decoration-none">
                            Workee - Multipurpose Shopify Theme</nuxt-link
                          >
                        </div>
                        <div class="d-block">
                          <v-card
                            class="d-flex justify-space-between"
                            flat
                            tile
                          >
                            <v-card flat tile class="text-secondary"
                              >By p-themes
                            </v-card>
                            <v-card flat tile>
                              <v-rating
                                v-model="rating"
                                background-color="white"
                                color="yellow accent-4"
                                dense
                                half-increments
                                hover
                                size="15"
                              ></v-rating>
                            </v-card>
                          </v-card>
                        </div>
                      </div>
                    </div>
                  </v-expand-transition>
                </v-img>
              </v-card>
            </v-hover>
          </v-col>
          <v-col cols="6" sm="6" md="6">
            <v-hover v-slot="{ hover }">
              <v-card class="mx-auto" color="grey lighten-4" max-width="600">
                <v-img
                  :aspect-ratio="17 / 8"
                  src="https://themeforest.img.customer.envatousercontent.com/files/353367507/01_preview.png?auto=compress%2Cformat&amp;fit=crop&amp;crop=top&amp;w=590&amp;h=300&amp;s=c7e46d23d9ce194594922660fabfca71"
                >
                  <v-expand-transition>
                    <div
                      v-if="hover"
                      class="
                        d-flex
                        transition-fast-in-fast-out
                        white
                        darken-2
                        v-card--reveal
                      "
                      style="height: 40%"
                    >
                      <div>
                        <div class="d-block">
                          <nuxt-link to="#" class="text-decoration-none">
                            Workee - Multipurpose Shopify Theme</nuxt-link
                          >
                        </div>
                        <div class="d-block">
                          <v-card
                            class="d-flex justify-space-between"
                            flat
                            tile
                          >
                            <v-card flat tile class="text-secondary"
                              >By p-themes
                            </v-card>
                            <v-card flat tile>
                              <v-rating
                                v-model="rating"
                                background-color="white"
                                color="yellow accent-4"
                                dense
                                half-increments
                                hover
                                size="15"
                              ></v-rating>
                            </v-card>
                          </v-card>
                        </div>
                      </div>
                    </div>
                  </v-expand-transition>
                </v-img>
              </v-card>
            </v-hover>
          </v-col>
          <v-col cols="6" sm="6" md="6">
            <v-hover v-slot="{ hover }">
              <v-card class="mx-auto" color="grey lighten-4" max-width="600">
                <v-img
                  :aspect-ratio="17 / 8"
                  src="https://themeforest.img.customer.envatousercontent.com/files/272093368/01_cover.png?auto=compress%2Cformat&amp;fit=crop&amp;crop=top&amp;w=590&amp;h=300&amp;s=b1888a18ddcabfac775d3645439021e0"
                >
                  <v-expand-transition>
                    <div
                      v-if="hover"
                      class="
                        d-flex
                        transition-fast-in-fast-out
                        white
                        darken-2
                        v-card--reveal
                      "
                      style="height: 40%"
                    >
                      <div>
                        <div class="d-block">
                          <nuxt-link to="#" class="text-decoration-none">
                            Workee - Multipurpose Shopify Theme</nuxt-link
                          >
                        </div>
                        <div class="d-block">
                          <v-card
                            class="d-flex justify-space-between"
                            flat
                            tile
                          >
                            <v-card flat tile class="text-secondary"
                              >By p-themes
                            </v-card>
                            <v-card flat tile>
                              <v-rating
                                v-model="rating"
                                background-color="white"
                                color="yellow accent-4"
                                dense
                                half-increments
                                hover
                                size="15"
                              ></v-rating>
                            </v-card>
                          </v-card>
                        </div>
                      </div>
                    </div>
                  </v-expand-transition>
                </v-img>
              </v-card>
            </v-hover>
          </v-col>
          <v-col cols="6" sm="6" md="6">
            <v-hover v-slot="{ hover }">
              <v-card class="mx-auto" color="grey lighten-4" max-width="600">
                <v-img
                  :aspect-ratio="17 / 8"
                  src="https://themeforest.img.customer.envatousercontent.com/files/338376038/01_listeo.png?auto=compress%2Cformat&amp;fit=crop&amp;crop=top&amp;w=590&amp;h=300&amp;s=2ac48780a786a56610d029bdf59fd961"
                >
                  <v-expand-transition>
                    <div
                      v-if="hover"
                      class="
                        d-flex
                        transition-fast-in-fast-out
                        white
                        darken-2
                        v-card--reveal
                      "
                      style="height: 40%"
                    >
                      <div>
                        <div class="d-block">
                          <nuxt-link to="#" class="text-decoration-none">
                            Workee - Multipurpose Shopify Theme</nuxt-link
                          >
                        </div>
                        <div class="d-block">
                          <v-card
                            class="d-flex justify-space-between"
                            flat
                            tile
                          >
                            <v-card flat tile class="text-secondary"
                              >By p-themes
                            </v-card>
                            <v-card flat tile>
                              <v-rating
                                v-model="rating"
                                background-color="white"
                                color="yellow accent-4"
                                dense
                                half-increments
                                hover
                                size="15"
                              ></v-rating>
                            </v-card>
                          </v-card>
                        </div>
                      </div>
                    </div>
                  </v-expand-transition>
                </v-img>
              </v-card>
            </v-hover>
          </v-col>
        </v-row>
      </v-col>
      <v-col cols="12" sm="4" md="4" class="pr-7">
        <h1>Unique themes and templates for every budget and every project.</h1>

        <v-row align="center" class="ma-10">
          <nuxt-link to="" class="text-decoration-none">
            <v-btn elevation="10" tile color="success" class="text-capitalize">
              View All Theme
            </v-btn>
          </nuxt-link>
        </v-row>
      </v-col>
    </v-row>
    <v-row class="my-16">
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
                    <v-btn elevation="2" outlined class="text-capitalize" color="#12A4E5">
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
                    <v-btn elevation="2" outlined class="text-capitalize" color="#12A4E5">
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
                    <v-btn elevation="2" outlined class="text-capitalize" color="#12A4E5">
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
                    <v-btn elevation="2" outlined class="text-capitalize" color="#12A4E5">
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
    <v-row class="my-16">
      <v-col cols="12" sm="6" md="6">
        <v-row class="grey lighten-5 px-6 py-5">
          <v-col cols="6" sm="6" md="6">
            <v-hover v-slot="{ hover }">
              <v-card class="mx-auto" color="grey lighten-4" max-width="600">
                <v-img
                  :aspect-ratio="17 / 8"
                  src="https://themeforest.img.customer.envatousercontent.com/files/287700081/01_preview_kant.png?auto=compress%2Cformat&amp;fit=crop&amp;crop=top&amp;w=590&amp;h=300&amp;s=314a8960fbb8fc04c3be5d5c0862cac8"
                >
                  <v-expand-transition>
                    <div
                      v-if="hover"
                      class="
                        d-flex
                        transition-fast-in-fast-out
                        white
                        darken-2
                        v-card--reveal
                      "
                      style="height: 40%"
                    >
                      <div>
                        <div class="d-block">
                          <nuxt-link
                            to="#"
                            class="text-decoration-none truncate-overflow"
                          >
                            Kant - Responsive Email for Startups: 50+ Sections +
                            MailChimp + Mailster + Shopify
                            Notifications</nuxt-link
                          >
                        </div>
                        <div class="d-block">
                          <v-card
                            class="d-flex justify-space-between"
                            flat
                            tile
                          >
                            <v-card flat tile class="text-secondary"
                              >By themesMountain
                            </v-card>
                            <v-card flat tile>
                              <v-rating
                                v-model="rating"
                                background-color="white"
                                color="yellow accent-4"
                                dense
                                half-increments
                                hover
                                size="15"
                              ></v-rating>
                            </v-card>
                          </v-card>
                        </div>
                      </div>
                    </div>
                  </v-expand-transition>
                </v-img>
              </v-card>
            </v-hover>
          </v-col>
          <v-col cols="6" sm="6" md="6">
            <v-hover v-slot="{ hover }">
              <v-card class="mx-auto" color="grey lighten-4" max-width="600">
                <v-img
                  :aspect-ratio="17 / 8"
                  src="https://themeforest.img.customer.envatousercontent.com/files/351501434/qwery-screens/01_Qwery.png?auto=compress%2Cformat&amp;fit=crop&amp;crop=top&amp;w=590&amp;h=300&amp;s=e173b3b0b6b7cb8a3690a333bff7b074"
                >
                  <v-expand-transition>
                    <div
                      v-if="hover"
                      class="
                        d-flex
                        transition-fast-in-fast-out
                        white
                        darken-2
                        v-card--reveal
                      "
                      style="height: 40%"
                    >
                      <div>
                        <div class="d-block">
                          <nuxt-link
                            to="#"
                            class="text-decoration-none truncate-overflow"
                          >
                            Qwery - Multi-Purpose Business WordPress Theme +
                            RTL</nuxt-link
                          >
                        </div>
                        <div class="d-block">
                          <v-card
                            class="d-flex justify-space-between"
                            flat
                            tile
                          >
                            <v-card flat tile class="text-secondary"
                              >By AnchoraThemes
                            </v-card>
                            <v-card flat tile>
                              <v-rating
                                v-model="rating"
                                background-color="white"
                                color="yellow accent-4"
                                dense
                                half-increments
                                hover
                                size="15"
                              ></v-rating>
                            </v-card>
                          </v-card>
                        </div>
                      </div>
                    </div>
                  </v-expand-transition>
                </v-img>
              </v-card>
            </v-hover>
          </v-col>
          <v-col cols="6" sm="6" md="6">
            <v-hover v-slot="{ hover }">
              <v-card class="mx-auto" color="grey lighten-4" max-width="600">
                <v-img
                  :aspect-ratio="17 / 8"
                  src="https://themeforest.img.customer.envatousercontent.com/files/353283834/01_preview.png?auto=compress%2Cformat&amp;fit=crop&amp;crop=top&amp;w=590&amp;h=300&amp;s=b838a84180d37e728e7907f18f6998f2"
                >
                  <v-expand-transition>
                    <div
                      v-if="hover"
                      class="
                        d-flex
                        transition-fast-in-fast-out
                        white
                        darken-2
                        v-card--reveal
                      "
                      style="height: 40%"
                    >
                      <div>
                        <div class="d-block">
                          <nuxt-link
                            to="#"
                            class="text-decoration-none truncate-overflow"
                          >
                            Hub - Responsive Multi-Purpose WordPress
                            Theme</nuxt-link
                          >
                        </div>
                        <div class="d-block">
                          <v-card
                            class="d-flex justify-space-between"
                            flat
                            tile
                          >
                            <v-card flat tile class="text-secondary"
                              >By LiquidThemes
                            </v-card>
                            <v-card flat tile>
                              <v-rating
                                v-model="rating"
                                background-color="white"
                                color="yellow accent-4"
                                dense
                                half-increments
                                hover
                                size="15"
                              ></v-rating>
                            </v-card>
                          </v-card>
                        </div>
                      </div>
                    </div>
                  </v-expand-transition>
                </v-img>
              </v-card>
            </v-hover>
          </v-col>
          <v-col cols="6" sm="6" md="6">
            <v-hover v-slot="{ hover }">
              <v-card class="mx-auto" color="grey lighten-4" max-width="600">
                <v-img
                  :aspect-ratio="17 / 8"
                  src="https://themeforest.img.customer.envatousercontent.com/files/305895364/preview/01_preview.jpg?auto=compress%2Cformat&amp;fit=crop&amp;crop=top&amp;w=590&amp;h=300&amp;s=d65f7892b398e743021b7f32d03efd3a"
                >
                  <v-expand-transition>
                    <div
                      v-if="hover"
                      class="
                        d-flex
                        transition-fast-in-fast-out
                        white
                        darken-2
                        v-card--reveal
                      "
                      style="height: 40%"
                    >
                      <div>
                        <div class="d-block">
                          <nuxt-link
                            to="#"
                            class="text-decoration-none truncate-overflow"
                          >
                            Litho – The Multipurpose HTML5 Template</nuxt-link
                          >
                        </div>
                        <div class="d-block">
                          <v-card
                            class="d-flex justify-space-between"
                            flat
                            tile
                          >
                            <v-card flat tile class="text-secondary"
                              >By ThemeZaa
                            </v-card>
                            <v-card flat tile>
                              <v-rating
                                v-model="rating"
                                background-color="white"
                                color="yellow accent-4"
                                dense
                                half-increments
                                hover
                                size="15"
                              ></v-rating>
                            </v-card>
                          </v-card>
                        </div>
                      </div>
                    </div>
                  </v-expand-transition>
                </v-img>
              </v-card>
            </v-hover>
          </v-col>
        </v-row>
      </v-col>
      <v-col cols="12" sm="6" md="6" class="pr-7">
        <v-row>
          <v-col cols="5"> </v-col>
          <v-col cols="7">
            <h1 class="float-right font-weight-light">
              We're the largest theme marketplace in the world
            </h1>
          </v-col>
        </v-row>

        <v-row class="mt-6">
          <v-card class="d-flex justify-space-between" flat tile>
            <v-card class="pa-2 ml-n9 mr-6" tile :elevation="18" width="67%">
              <v-avatar class="mt-6 ml-6">
                <img
                  loading="lazy"
                  width="48"
                  height="48"
                  class="home-value_proposition_block_component__tileIcon"
                  alt="popular"
                  src="https://assets.market-storefront.envato-static.com/storefront/packs/media/images/home/value-prop-icons/popular-f17ddb16bbcfb47b4d24656ef9bf5fa3.svg"
                />
              </v-avatar>
              <h5 class="pa-4">Home of the most popular themes in the world</h5>
            </v-card>
            <v-card class="pa-2 mr-6" tile width="67%" :elevation="18">
              <v-avatar class="mt-6 ml-6">
                <img
                  loading="lazy"
                  width="48"
                  height="48"
                  class="home-value_proposition_block_component__tileIcon"
                  alt="support"
                  src="https://assets.market-storefront.envato-static.com/storefront/packs/media/images/home/value-prop-icons/support-eaac5e66c8a5454ed083346094e404cd.svg"
                />
              </v-avatar>
              <h5 class="pa-4">
                Clear documentation and theme support available
              </h5>
            </v-card>
            <v-card class="pa-2" tile width="67%" :elevation="18">
              <v-avatar class="mt-6 ml-6">
                <img
                  loading="lazy"
                  width="48"
                  height="48"
                  class="home-value_proposition_block_component__tileIcon"
                  alt="quality"
                  src="https://assets.market-storefront.envato-static.com/storefront/packs/media/images/home/value-prop-icons/quality-1b3c0c21025219fdff69803474a2e018.svg"
                />
              </v-avatar>
              <h5 class="pa-4">Home of the most popular themes in the world</h5>
            </v-card>
          </v-card>
        </v-row>
      </v-col>
    </v-row>

    <v-row class="my-16">
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
                  <v-btn elevation="2" outlined class="text-capitalize" color="#12A4E5">
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
                  <v-btn elevation="2" outlined class="text-capitalize" color="#12A4E5">
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
                  <v-btn elevation="2" outlined class="text-capitalize" color="#12A4E5">
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
                  <v-btn elevation="2" outlined class="text-capitalize" color="#12A4E5">
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
                  <v-btn elevation="2" outlined class="text-capitalize" color="#12A4E5">
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
                  <v-btn elevation="2" outlined class="text-capitalize" color="#12A4E5">
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
                  <v-btn elevation="2" outlined class="text-capitalize" color="#12A4E5">
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
                  <v-btn elevation="2" outlined class="text-capitalize" color="#12A4E5">
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

    <v-row class="my-16 grey lighten-5">
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
                  <v-btn elevation="2" outlined class="text-capitalize" color="#12A4E5">
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
                  <v-btn elevation="2" outlined class="text-capitalize" color="#12A4E5">
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
              <h4 class=" ml-3">
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
                  <v-btn elevation="2" outlined class="text-capitalize" color="#12A4E5">
                    Preview</v-btn
                  >
                </v-card>
              </v-card>
            </v-card>
          </v-card>
        </v-col>
      </v-row>
    </v-row>

    <v-row class="my-16">
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
                <h4 class=" ml-3">
                  <nuxt-link
                    to="#"
                    class="text-decoration-none black--text"
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
                    <v-btn elevation="2" outlined class="text-capitalize" color="#12A4E5">
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
                <h4 class=" ml-3">
                  <nuxt-link
                    to="#"
                    class="text-decoration-none black--text"
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
                    <v-btn elevation="2" outlined class="text-capitalize" color="#12A4E5">
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
                <h4 class=" ml-3">
                  <nuxt-link
                    to="#"
                    class="text-decoration-none black--text"
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
                    <v-btn elevation="2" outlined class="text-capitalize" color="#12A4E5">
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
                <h4 class=" ml-3">
                  <nuxt-link
                    to="#"
                    class="text-decoration-none black--text"
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
                    <v-btn elevation="2" outlined class="text-capitalize" color="#12A4E5">
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
    <v-row class="my-16 grey lighten-5">
      <v-col cols="12" sm="4" md="4">
        <v-card
          class="d-flex align-center grey lighten-5 mb-4"
          flat
          height="100%"
          tile
        >
          <v-card flat tile>
            <h1 class="ml-16 pa-7 display-2">Unlimited downloads</h1>
            <h3 class="ml-16 pl-7 text--secondary">
              Enjoy millions of web templates, plugins, videos & more with
              Envato Elements. From $16.50/month.
            </h3>
            <img
              loading="lazy"
              class="ma-5 pl-16"
              src="https://assets.market-storefront.envato-static.com/storefront/packs/media/images/logos/envato-elements-4de52b67c96ca63c1b764d39b573a7af.svg"
              width="300"
              height="40"
              alt="Elements logo"
            />
            <v-row class="ml-10 mt-2 pl-13">
              <nuxt-link to="" class="text-decoration-none">
                <v-btn
                  elevation="10"
                  tile
                  color="success"
                  class="text-capitalize"
                >
                  Go to Envato Elements
                </v-btn>
              </nuxt-link>
            </v-row>
          </v-card>
        </v-card>
      </v-col>
      <v-col cols="12" sm="8" md="8" class="pa-16">
        <v-row>
          <v-col cols="6" sm="4" md="4">
            <v-card flat class="mx-auto pb-2" width="100%" :elevation="4">
              <div class="mb-2">
                <img
                  src="https://themeforest.img.customer.envatousercontent.com/files/223514661/preview.jpg?auto=compress%2Cformat&amp;fit=crop&amp;crop=top&amp;w=590&amp;h=300&amp;s=8faa8c4ff7a36b1402d24911bb731ef4"
                  loading="lazy"
                  width="100%"
                  height="90%"
                  class="d-block"
                />
              </div>
              <v-card class="d-flex justify-space-between" flat tile>
                <v-card class="" flat tile>
                  <h4 class="truncate-overflow ml-3">
                    <nuxt-link to="#" class="text-decoration-none black--text"
                      >LiveKitchen - HTML5 Restaurant Template</nuxt-link
                    >
                  </h4>
                  <nuxt-link to="#" class="text-decoration-none">
                    <h5 class="text--secondary ml-3 mb-3">
                      By HTMLguru Web Templates
                    </h5>
                  </nuxt-link>
                </v-card>
                <v-card class="pa-2" flat tile dense>
                  <v-btn elevation="2" outlined class="text-capitalize pa-0" color="pink">
                    View</v-btn
                  >
                </v-card>
              </v-card>
            </v-card>
          </v-col>
          <v-col cols="6" sm="4" md="4">
            <v-card flat class="mx-auto pb-2" width="100%" :elevation="4">
              <div class="mb-2">
                <img
                src="https://themeforest.img.customer.envatousercontent.com/files/257433867/01_aspero-preview.jpg?auto=compress%2Cformat&amp;fit=crop&amp;crop=top&amp;w=590&amp;h=300&amp;s=90d103945ba5914aa398c626d1d47f02"
                loading="lazy"
                  width="100%"
                  height="90%"
                  class="d-block"
                />
              </div>
              <v-card class="d-flex justify-space-between" flat tile>
                <v-card class="" flat tile>
                  <h4 class="truncate-overflow ml-3">
                    <nuxt-link to="#" class="text-decoration-none black--text"
                      >LiveKitchen - HTML5 Restaurant Template</nuxt-link
                    >
                  </h4>
                  <nuxt-link to="#" class="text-decoration-none">
                    <h5 class="text--secondary ml-3 mb-3">
                      By HTMLguru Web Templates
                    </h5>
                  </nuxt-link>
                </v-card>
                <v-card class="pa-2" flat tile dense>
                  <v-btn elevation="2" outlined class="text-capitalize" color="pink">
                    View</v-btn
                  >
                </v-card>
              </v-card>
            </v-card>
          </v-col>
          <v-col cols="6" sm="4" md="4">
            <v-card flat class="mx-auto pb-2" width="100%" :elevation="4">
              <div class="mb-2">
                <img 
                loading="lazy"
                src="https://themeforest.img.customer.envatousercontent.com/files/124171908/preview.jpg?auto=compress%2Cformat&amp;fit=crop&amp;crop=top&amp;w=590&amp;h=300&amp;s=cd71d1651cdc522efbddd4287c540103"
                  width="100%"
                  height="90%"
                  class="d-block"
                />
              </div>
              <v-card class="d-flex justify-space-between" flat tile>
                <v-card class="" flat tile>
                  <h4 class="truncate-overflow ml-3">
                    <nuxt-link to="#" class="text-decoration-none black--text"
                      >LiveKitchen - HTML5 Restaurant Template</nuxt-link
                    >
                  </h4>
                  <nuxt-link to="#" class="text-decoration-none">
                    <h5 class="text--secondary ml-3 mb-3">
                      By HTMLguru Web Templates
                    </h5>
                  </nuxt-link>
                </v-card>
                <v-card class="pa-2" flat tile dense>
                  <v-btn elevation="2" outlined class="text-capitalize" color="pink">
                    View</v-btn
                  >
                </v-card>
              </v-card>
            </v-card>
          </v-col>
          <v-col cols="6" sm="4" md="4">
            <v-card flat class="mx-auto pb-2" width="100%" :elevation="4">
              <div class="mb-2">
                <img
                src="https://themeforest.img.customer.envatousercontent.com/files/236210600/01_preview.jpg?auto=compress%2Cformat&amp;fit=crop&amp;crop=top&amp;w=590&amp;h=300&amp;s=bbe608eeb18416e2432135c3191e7d84"
                  loading="lazy"
                  width="100%"
                  height="90%"
                  class="d-block"
                />
              </div>
              <v-card class="d-flex justify-space-between" flat tile>
                <v-card class="" flat tile>
                  <h4 class="truncate-overflow ml-3">
                    <nuxt-link to="#" class="text-decoration-none black--text"
                      >LiveKitchen - HTML5 Restaurant Template</nuxt-link
                    >
                  </h4>
                  <nuxt-link to="#" class="text-decoration-none">
                    <h5 class="text--secondary ml-3 mb-3">
                      By HTMLguru Web Templates
                    </h5>
                  </nuxt-link>
                </v-card>
                <v-card class="pa-2" flat tile dense>
                  <v-btn elevation="2" outlined class="text-capitalize" color="pink">
                    View</v-btn
                  >
                </v-card>
              </v-card>
            </v-card>
          </v-col>
          <v-col cols="6" sm="4" md="4">
            <v-card flat class="mx-auto pb-2" width="100%" :elevation="4">
              <div class="mb-2">
                <img
                 src="https://themeforest.img.customer.envatousercontent.com/files/175233813/preview.jpg?auto=compress%2Cformat&amp;fit=crop&amp;crop=top&amp;w=590&amp;h=300&amp;s=57e80546beca8867bee68adbdc7793f4"
                  loading="lazy"
                  width="100%"
                  height="90%"
                  class="d-block"
                />
              </div>
              <v-card class="d-flex justify-space-between" flat tile>
                <v-card class="" flat tile>
                  <h4 class="truncate-overflow ml-3">
                    <nuxt-link to="#" class="text-decoration-none black--text"
                      >LiveKitchen - HTML5 Restaurant Template</nuxt-link
                    >
                  </h4>
                  <nuxt-link to="#" class="text-decoration-none">
                    <h5 class="text--secondary ml-3 mb-3">
                      By HTMLguru Web Templates
                    </h5>
                  </nuxt-link>
                </v-card>
                <v-card class="pa-2" flat tile dense>
                  <v-btn elevation="2" outlined class="text-capitalize" color="pink">
                    View</v-btn
                  >
                </v-card>
              </v-card>
            </v-card>
          </v-col>
          <v-col cols="6" sm="4" md="4">
            <v-card flat class="mx-auto pb-2" width="100%" :elevation="4">
              <div class="mb-2">
                <img
                  src="https://themeforest.img.customer.envatousercontent.com/files/257152934/ThemePreview.jpg?auto=compress%2Cformat&amp;fit=crop&amp;crop=top&amp;w=590&amp;h=300&amp;s=5cf18f61778c3831032d227a12938fc3"
                  loading="lazy"
                  width="100%"
                  height="90%"
                  class="d-block"
                />
              </div>
              <v-card class="d-flex justify-space-between" flat tile>
                <v-card class="" flat tile>
                  <h4 class="truncate-overflow ml-3">
                    <nuxt-link to="#" class="text-decoration-none black--text"
                      >LiveKitchen - HTML5 Restaurant Template</nuxt-link
                    >
                  </h4>
                  <nuxt-link to="#" class="text-decoration-none">
                    <h5 class="text--secondary ml-3 mb-3">
                      By HTMLguru Web Templates
                    </h5>
                  </nuxt-link>
                </v-card>
                <v-card class="pa-2" flat tile dense>
                  <v-btn elevation="2" outlined class="text-capitalize" color="pink">
                    View</v-btn
                  >
                </v-card>
              </v-card>
            </v-card>
          </v-col>
        </v-row>
      </v-col>
    </v-row>

    <v-row class="my-16">
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
      <v-row>
        <v-col cols="6" sm="3" md="3">
          <v-card
            flat
            class="mx-auto pb-2"
            width="100%"
            height="90%"
            :elevation="6"
          >
            <v-img
             src="https://s3.envato.com/files/349991353/DSC02792.jpg"
              class="white--text align-end"
              gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
              height="160px"
            >
              <h3 class="float-right pa-2" color="#9FA2A3"> Photo</h3>
            </v-img>
            
            <v-card flat class="pa-4">
              <h4 class="truncate-overflow">
                <nuxt-link to="#" class="text-decoration-none black--text">
                <h5>  Pleased redhead woman student watches training webinar,</h5>
                  </nuxt-link>
              </h4>
              <nuxt-link to="#" class="text-decoration-none">
                <h5 class="text--disabled">
                  by StudioVK in photos
                </h5>
              </nuxt-link>
            </v-card>
          </v-card>
        </v-col>
        <v-col cols="6" sm="3" md="3">
          <v-card
            flat
            class="mx-auto pb-2"
            width="100%"
            height="90%"
            :elevation="6"
          >
            <v-img
            src="https://camo.envatousercontent.com/8dcb0b93329bbd3ea704ab13d4a69b8a58bc89e4/68747470733a2f2f636c6475702e636f6d2f4c636d38496a4b7363422d3330303078333030302e706e67"
              class="white--text align-end"
              gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
              height="160px"
            >
              <h3 class="float-right pa-2" color="#9FA2A3"> Audio</h3>
            </v-img>
            
            <v-card flat class="pa-4">
              <h4 class="truncate-overflow">
                <nuxt-link to="#" class="text-decoration-none black--text">
                <h5>  China Japan Korea Dubstep</h5>
                  </nuxt-link>
              </h4>
              <nuxt-link to="#" class="text-decoration-none">
                <h5 class="text--disabled">
                 By Nuclearmetal
                </h5>
              </nuxt-link>
            </v-card>
          </v-card>
        </v-col>
        <v-col cols="6" sm="3" md="3">
          <v-card
            flat
            class="mx-auto pb-2"
            width="100%"
            height="90%"
            :elevation="6"
          >
            <v-img
           src="https://codecanyon.img.customer.envatousercontent.com/files/293693826/preview.jpg?auto=compress%2Cformat&amp;q=80&amp;fit=crop&amp;crop=top&amp;max-h=8000&amp;max-w=590&amp;s=47e85f6db6d6a1073d014b9a30bc8607"
              class="white--text align-end"
              gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
              height="160px"
            >
              <h3 class="float-right pa-2" color="#9FA2A3"> Code</h3>
            </v-img>
            
            <v-card flat class="pa-4">
              <h4 class="truncate-overflow">
                <nuxt-link to="#" class="text-decoration-none black--text">
                <h5> Mediabay - WordPress Media Library Folders</h5>
                  </nuxt-link>
              </h4>
              <nuxt-link to="#" class="text-decoration-none">
                <h5 class="text--disabled">
                  By codedraft
                </h5>
              </nuxt-link>
            </v-card>
          </v-card>
        </v-col>
        
        <v-col cols="6" sm="3" md="3">
          <v-card
            flat
            class="mx-auto pb-2"
            width="100%"
            height="90%"
            :elevation="6"
          >
            <v-img
            src="https://videohive.img.customer.envatousercontent.com/files/87661948/590x300.png?auto=compress%2Cformat&amp;fit=crop&amp;crop=top&amp;max-h=8000&amp;max-w=590&amp;s=40d11cff1c102a24f2d0e54ed728a003"
             class="white--text align-end"
              gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
              height="160px"
            >
              <h3 class="float-right pa-2" color="#9FA2A3"> Video</h3>
            </v-img>
            
            <v-card flat class="pa-4">
              <h4 class="truncate-overflow">
                <nuxt-link to="#" class="text-decoration-none black--text">
                <h5> Vintage Label Toolkit</h5>
                  </nuxt-link>
              </h4>
              <nuxt-link to="#" class="text-decoration-none">
                <h5 class="text--disabled">
                  By alexandersaunki
                </h5>
              </nuxt-link>
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
