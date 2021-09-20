<template>
  <v-container>
    <IndividualSubHeader />
    <IndividualBreadcrumbReview />
    <v-row no-gutters class="mt-n5 ml-3">
      <v-col md="10" offset-md="1" class="pl-5">
        <h1 class="text--primary">
          Discussion on Kalles - Clean, Versatile, Responsive Shopify Theme -
          RTL support
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
                <v-card class="pa-2 mt-5" tile width="720px">
                  <v-row width="720px">
                    <v-col cols="2">
                      <img
                        class="ma-1"
                        src="https://s3.envato.com/files/265668596/logo80png.png"
                        width="80"
                        height="80"
                        alt="The4"
                      />
                    </v-col>
                    <v-col cols="10" class="">
                      <div class="pt-3">
                        <div class="d-inline title pa-2">
                          The4 supports this item
                        </div>
                        <div class="d-inline pa-2">
                          <v-btn x-small class="info ml-n4">supported</v-btn>
                        </div>
                      </div>
                      <p class="text--secondary text-caption ml-2">
                        This author's response time can be up to
                        <span class="font-weight-bold">2 business days.</span>
                      </p>
                    </v-col>
                  </v-row>
                </v-card>
                <v-row>
                  <v-col cols="5">
                    <v-text-field
                      class="mt-4"
                      placeholder="Search comments"
                      outlined
                      dense
                      tile
                      append-icon="mdi-magnify"
                    ></v-text-field>
                  </v-col>
                  <v-col cols="7">
                    <v-checkbox
                      v-model="ex4"
                      class="mb-5"
                      label="From buyers and authors only"
                      color="red"
                      value="red"
                      hide-details
                    ></v-checkbox>
                  </v-col>
                </v-row>

                <v-row class="title">
                  <span class="ml-5"> 473 comments found.</span>
                </v-row>
                <v-row>
                  <v-card class="pa-4 mt-5 ml-3" tile width="720px">
                    <img
                      class="d-inline"
                      width="40"
                      height="40"
                      alt="neslot"
                      src="https://public-assets.envato-static.com/assets/common/icons-buttons/default-user-2962fd43ee315eafee8bfc08f02fee84687beb0499de44e5ab2873399944b0fe.jpg"
                    />
                    <span class="d-inline ml-5 text-center mb-n5"
                      ><nuxt-link
                        to="#"
                        class="text-decoration-none font-weight-bold"
                        >neslot</nuxt-link
                      ></span
                    >
                    <h5 class="text--secondary pb-4">Hi dear!</h5>
                    <p>
                      Does this theme support full homepage checkout (with
                      product options) – like this:
                      https://cdn.imgchest.com/files/pyq9c5wpk42.png I see that
                      the features include fast page speed, does this include
                      all core web vitals (including the very annoying CLS)?
                    </p>
                    <v-divider></v-divider>
                    <v-card flat dense tile class="pl-10 pt-5">
                      <img
                        src="https://s3.envato.com/files/350254110/z2652163368830_56c0a0349bbc440b0de4828762136ddb.jpg"
                        width="40"
                        height="40"
                        alt="The4_Support"
                      />
                      <span class="d-inline ml-5 text-center mb-n5"
                        ><nuxt-link
                          to="#"
                          class="text-decoration-none font-weight-bold"
                        >
                          The4_Support
                          <v-btn x-small class="grey"
                            >Author Team</v-btn
                          ></nuxt-link
                        ></span
                      >
                      <h5 class="text--secondary pb-4">Hi dear!</h5>
                      <p>
                        Does this theme support full homepage checkout (with
                        product options) – like this:
                        https://cdn.imgchest.com/files/pyq9c5wpk42.png I see
                        that the features include fast page speed, does this
                        include all core web vitals (including the very annoying
                        CLS)?
                      </p>
                    </v-card>
                  </v-card>
                </v-row>
                <v-row>
                  <v-card class="pa-4 mt-5 ml-3" tile width="720px">
                    <img
                      class="d-inline"
                      width="40"
                      height="40"
                      alt="neslot"
                      src="https://public-assets.envato-static.com/assets/common/icons-buttons/default-user-2962fd43ee315eafee8bfc08f02fee84687beb0499de44e5ab2873399944b0fe.jpg"
                    />
                    <span class="d-inline ml-5 text-center mb-n5"
                      ><nuxt-link
                        to="#"
                        class="text-decoration-none font-weight-bold"
                        >PixmediaLda</nuxt-link
                      ></span
                    >
                    <p>
                      Does this theme have support for product weights? Most of
                      them i only see the variations work for size and colors.
                    </p>
                    <v-divider></v-divider>
                    <v-card flat dense tile class="pl-10 pt-5">
                      <img
                        src="https://s3.envato.com/files/350254110/z2652163368830_56c0a0349bbc440b0de4828762136ddb.jpg"
                        width="40"
                        height="40"
                        alt="The4_Support"
                      />
                      <span class="d-inline ml-5 text-center mb-n5"
                        ><nuxt-link
                          to="#"
                          class="text-decoration-none font-weight-bold"
                        >
                          The4_Support
                          <v-btn x-small class="grey"
                            >Author Team</v-btn
                          ></nuxt-link
                        ></span
                      >
                      <h5 class="text--secondary pb-4">Hi dear!</h5>
                      <p>
                        Hi, thank you for your question, Kalles theme support
                        product weights. Please see the video for example how it
                        works:
                        https://drive.google.com/file/d/1CsQARQWaph8_TG-ZcVIsKWAq7YMrkPxD/view
                      </p>
                    </v-card>
                  </v-card>
                </v-row>
                <v-row>
                  <v-card class="pa-4 mt-5 ml-3" tile width="720px">
                    <img
                      class="d-inline"
                      width="40"
                      height="40"
                      alt="neslot"
                      src="https://public-assets.envato-static.com/assets/common/icons-buttons/default-user-2962fd43ee315eafee8bfc08f02fee84687beb0499de44e5ab2873399944b0fe.jpg"
                    />
                    <span class="d-inline ml-5 text-center mb-n5"
                      ><nuxt-link
                        to="#"
                        class="text-decoration-none font-weight-bold"
                        >Philosoph</nuxt-link
                      ></span
                    >
                    <p>
                      We never lost so much time in design basics, because the
                      design is so terrible out of the box. Blogpost before:
                      https://ibb.co/6P4LJcD After switched to your theme the
                      blog post looks like this: https://ibb.co/hmKtQCq Your
                      blog layout looks like terrible word document and nothing
                      about blog design. Also nothing about UX and about
                      “premium” theme out of the box. The design options in
                      theme panel did not have good options to get any great
                      design. Do you have any update for blog soon? So we need
                      to add again 4 or 5 hours into custom coding again to fix
                      basic needs in a premium paid theme? :-(
                    </p>
                    <v-divider></v-divider>
                    <v-card flat dense tile class="pl-10 pt-5">
                      <img
                        src="https://s3.envato.com/files/350254110/z2652163368830_56c0a0349bbc440b0de4828762136ddb.jpg"
                        width="40"
                        height="40"
                        alt="The4_Support"
                      />
                      <span class="d-inline ml-5 text-center mb-n5"
                        ><nuxt-link
                          to="#"
                          class="text-decoration-none font-weight-bold"
                        >
                          The4_Support
                          <v-btn x-small class="grey"
                            >Author Team</v-btn
                          ></nuxt-link
                        ></span
                      >
                      <h5 class="text--secondary pb-4">Hi dear!</h5>
                      <p>
                        Hi! Here is option to setup blog post layout in our
                        theme: https://prnt.sc/1rhm7d2 The content will be
                        displayed like this for example:
                        https://kalles-demo.myshopify.com/blogs/life-style/spring-summer-trending-2020
                        Also it allows you to use shortcode on posts
                        (https://prnt.sc/1rhn0bl) if you have any
                        difficulties/problem while using our theme, can you
                        please help me open a ticket at http://support.the4.co/
                        so my team can check it soonest :) Thank you!
                      </p>
                    </v-card>
                  </v-card>
                </v-row>
                <v-row>
                  <v-card class="pa-4 mt-5 ml-3" tile width="720px">
                    <img
                      class="d-inline"
                      width="40"
                      height="40"
                      alt="neslot"
                      src="https://public-assets.envato-static.com/assets/common/icons-buttons/default-user-2962fd43ee315eafee8bfc08f02fee84687beb0499de44e5ab2873399944b0fe.jpg"
                    />
                    <span class="d-inline ml-5 text-center mb-n5"
                      ><nuxt-link
                        to="#"
                        class="text-decoration-none font-weight-bold"
                        >yzxglobal</nuxt-link
                      ></span
                    >
                    <p>
                      Hi Kalles/The4_Support, Can we set the default site
                      language to German from “Edit languages” -> “Change theme
                      language” on Shopify? We don’t need a multi-lingual site
                      and we don’t need any translation App. We just need a
                      German site. For some other themes, when we “Change theme
                      language” Shopify will report “Your active theme does not
                      contain German translations”. Thanks!
                    </p>
                    <nuxt-link to="#">4 other comments</nuxt-link>
                    <v-divider></v-divider>
                    <v-card flat dense tile class="pl-10 pt-5">
                      <img
                        src="https://s3.envato.com/files/350254110/z2652163368830_56c0a0349bbc440b0de4828762136ddb.jpg"
                        width="40"
                        height="40"
                        alt="The4_Support"
                      />
                      <span class="d-inline ml-5 text-center mb-n5"
                        ><nuxt-link
                          to="#"
                          class="text-decoration-none font-weight-bold"
                        >
                          The4_Support
                          <v-btn x-small class="grey"
                            >Author Team</v-btn
                          ></nuxt-link
                        ></span
                      >
                      <h5 class="text--secondary pb-4">Hi dear!</h5>
                      <p>
                        Hi, yes you can create a translation for the theme with
                        Edit Language option. Please see my screenshots for
                        reference: https://prnt.sc/1s4h0yb
                        https://prnt.sc/1s4h4bt Thank you :)
                      </p>
                    </v-card>
                    <v-divider></v-divider>
                    <v-card flat dense tile class="pl-10 pt-5">
                      <img
                        src="https://public-assets.envato-static.com/assets/common/icons-buttons/default-user-2962fd43ee315eafee8bfc08f02fee84687beb0499de44e5ab2873399944b0fe.jpg"
                        width="40"
                        height="40"
                        alt="The4_Support"
                      />
                      <span class="d-inline ml-5 text-center mb-n5"
                        ><nuxt-link
                          to="#"
                          class="text-decoration-none font-weight-bold"
                        >
                          yzxglobal
                        </nuxt-link></span
                      >
                      <p>
                        Hi Kalles/The4_Support, Thank you for your prompt
                        answer! One thing to confirm, we need to manually input
                        these German theme texts (like “In den Warenkorb legen”
                        (Add to cart)) one by one by ourselves. Is that right?
                        Thank you very much!
                      </p>
                    </v-card>
                    <v-divider></v-divider>
                    <v-card flat dense tile class="pl-10 pt-5">
                      <img
                        src="https://s3.envato.com/files/350254110/z2652163368830_56c0a0349bbc440b0de4828762136ddb.jpg"
                        width="40"
                        height="40"
                        alt="The4_Support"
                      />
                      <span class="d-inline ml-5 text-center mb-n5"
                        ><nuxt-link
                          to="#"
                          class="text-decoration-none font-weight-bold"
                        >
                          The4_Support
                          <v-btn x-small class="grey"
                            >Author Team</v-btn
                          ></nuxt-link
                        ></span
                      >
                      <h5 class="text--secondary pb-4">Hi dear!</h5>
                      <p>
                        Hi! Here is option to setup blog post layout in our
                        theme: https://prnt.sc/1rhm7d2 The content will be
                        displayed like this for example:
                        https://kalles-demo.myshopify.com/blogs/life-style/spring-summer-trending-2020
                        Also it allows you to use shortcode on posts
                        (https://prnt.sc/1rhn0bl) if you have any
                        difficulties/problem while using our theme, can you
                        please help me open a ticket at http://support.the4.co/
                        so my team can check it soonest :) Thank you!
                      </p>
                    </v-card>
                  </v-card>
                </v-row>
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
            <div class="text-center mt-5">
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
