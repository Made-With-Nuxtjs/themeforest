<template>
  <v-container>
    <IndividualSubHeader />
    <IndividualBreadcrumb />
    <v-row no-gutters class="mt-n5">
      <v-col md="10" offset-md="1" class="pl-5">
        <h1 class="text--primary">
          Kalles - Clean, Versatile, Responsive Shopify Theme - RTL support
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
                background-color="white"
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

        <v-card flat grey lighten-4>
          <v-toolbar flat>
            <template #extension>
              <v-tabs v-model="tab" align-with-title>
                <v-tabs-slider></v-tabs-slider>
                <v-tab class="text-capitalize text-caption">Item Details</v-tab>
                <v-tab class="text-capitalize text-caption"> Reviews </v-tab>
                <v-tab class="text-capitalize text-caption"> Comments </v-tab>
                <v-tab class="text-capitalize text-caption"> Supports </v-tab>
              </v-tabs>
            </template>
          </v-toolbar>

          <v-tabs-items v-model="tab">
            <v-tab-item>
              <v-card flat>
                <!-- iTEM dETAILS -->
                <v-row no-gutters>
                  <v-col cols="12" sm="6" md="8" class="class=" ml-16>
                    <v-card class="pa-2" tile width="720px">
                      <img
                        alt="Kalles - Clean, Versatile, Responsive Shopify Theme - RTL support - Fashion Shopify"
                        width="690"
                        height="300"
                        srcset="
                          https://themeforest.img.customer.envatousercontent.com/files/353452783/preview.__large_preview.jpg?auto=compress%2Cformat&amp;q=80&amp;fit=crop&amp;crop=top&amp;max-h=8000&amp;max-w=590&amp;s=fa6088598ed6116bdce6ec832f205add 590w,
                          https://themeforest.img.customer.envatousercontent.com/files/353452783/preview.__large_preview.jpg?auto=compress%2Cformat&amp;q=80&amp;fit=crop&amp;crop=top&amp;max-h=6780&amp;max-w=500&amp;s=8216bf6f3d3b99180d64b5e3ba0f6380 500w,
                          https://themeforest.img.customer.envatousercontent.com/files/353452783/preview.__large_preview.jpg?auto=compress%2Cformat&amp;q=80&amp;fit=crop&amp;crop=top&amp;max-h=5424&amp;max-w=400&amp;s=e4e4f6376aae1b0dc1288de1eb76a07f 400w,
                          https://themeforest.img.customer.envatousercontent.com/files/353452783/preview.__large_preview.jpg?auto=compress%2Cformat&amp;q=80&amp;fit=crop&amp;crop=top&amp;max-h=4068&amp;max-w=300&amp;s=68e0cd23fcf2733d9e613c0c13d3890b 300w
                        "
                        sizes="(min-width: 1024px) 590px, (min-width: 1px) 100vw, 600px"
                        src="https://themeforest.img.customer.envatousercontent.com/files/353452783/preview.__large_preview.jpg?auto=compress%2Cformat&amp;q=80&amp;fit=crop&amp;crop=top&amp;max-h=8000&amp;max-w=590&amp;s=fa6088598ed6116bdce6ec832f205add"
                      />
                      <div align="center" class="pa-3">
                        <v-btn
                          small
                          color="primary"
                          dark
                          class="text-capitalize"
                        >
                          Preview Item
                          <v-icon>mdi-view-quilt-outline</v-icon>
                        </v-btn>
                        <v-btn
                          small
                          color="grey"
                          dark
                          class="text-capitalize ml-2"
                        >
                          Screen Short
                          <v-icon>mdi-view-quilt-outline</v-icon>
                        </v-btn>
                      </div>
                    </v-card>
                    <v-card
                      class="d-flex justify-space-around mb-6 mr-7 mt-5"
                      flat
                      tile
                    >
                      <v-btn class="text-capitalize">
                        <v-icon class="mr-3">mdi-heart</v-icon>
                        Add to Favorite
                      </v-btn>

                      <v-btn class="text-capitalize mr-8">
                        <v-icon class="mr-3">mdi-folder-open</v-icon>
                        Add to Collection
                      </v-btn>
                    </v-card>
                    <v-card
                      class="d-flex justify-space-around mb-6 mr-7"
                      flat
                      tile
                    >
                      <p>
                        We’ve built a product that makes your startup look
                        professional, elegant and focused. Start building a
                        beautiful email campaign today. Being startup, time is
                        always a factor. This is why we have carefully created
                        ready-to-use modules that you can easily piece together
                        to create a stunning campaign in a matter of minutes. It
                        comes with 50+ purpose-built sections and 12 example
                        demo layouts to get you started! For the first time on
                        ThemeForest you can buy an HTML template together with a
                        complementary Email template so that you can build a
                        stunning website and launch professional email campaign.
                        Get the HTML version <nuxt-link to="#">here</nuxt-link>
                      </p>
                    </v-card>
                    <a
                      href="https://1.envato.market/c/1288411/275988/4415?subId1=landing&amp;subId2=buy_now&amp;subId3=https%3A%2F%2Fthemeforest.net%2Fcart%2Fconfigure_before_adding%2F26320622%3Flicense%3Dregular%26ref%3Dthe4%26size%3Dsource%26support%3Dbundle_12month&amp;u=https%3A%2F%2Fthemeforest.net%2Fcart%2Fconfigure_before_adding%2F26320622%3Flicense%3Dregular%26ref%3Dthe4%26size%3Dsource%26support%3Dbundle_12month"
                      rel="nofollow"
                      ><img
                        src="https://camo.envatousercontent.com/61ee42bfc8ddb9bb2bee6b45d93ab5dbecea2c71/68747470733a2f2f7468656d65732e746865342e636f2f6b616c6c65732d6465732f68746d6c2d696e636c7564652e6a7067"
                        alt="Kalles - Clean, Versatile, Responsive Shopify Theme - RTL support - 1"
                    /></a>
                    <img
                      src="https://camo.envatousercontent.com/1ae43d81d2fcbe91cf3b2fe8e345445bbd8e4e91/68747470733a2f2f7468656d65732e746865342e636f2f6b616c6c65732d6465732f76322e342e474946"
                      alt="Kalles - Clean, Versatile, Responsive Shopify Theme - RTL support - 2"
                    />
                    <img
                      src="https://camo.envatousercontent.com/5885a07e7f35f3752b584d33a6aba562331fbe4d/68747470733a2f2f63646e2e73686f706966792e636f6d2f732f66696c65732f312f303333322f363432302f353936332f66696c65732f7570646174655f322e332e6a70673f763d31363137303033333131"
                      alt="Kalles - Clean, Versatile, Responsive Shopify Theme - RTL support - 3"
                    />
                    <img
                      src="https://camo.envatousercontent.com/8d2f1a5ee7a089570d06bf3a9fc5a0e6a818b867/68747470733a2f2f7468656d65732e746865342e636f2f6b616c6c65732d6465732f6e756d6265722d312e6a7067"
                      alt="Kalles - Clean, Versatile, Responsive Shopify Theme - RTL support - 4"
                    />
                    <img
                      src="https://camo.envatousercontent.com/0987a8efce8d75d7ca8b51869f9054b6294fd812/68747470733a2f2f7468656d65732e746865342e636f2f6b616c6c65732d6465732f426573742d72617465642d73656c6c696e672e6a7067"
                      alt="Kalles - Clean, Versatile, Responsive Shopify Theme - RTL support - 5"
                    />
                    <p>
                      Whatever you’re selling, Kalles is the only Shopify theme
                      you’ll need to create a powerful online store that will
                      give your customers smooth and seamless shopping
                      experience. Modern design, minimalist feel, and a range of
                      special demos, Kalles is designed for an array of
                      different online retailers. Display your products in style
                      and make it easy for your customers to browse, choose and
                      purchase. Easy, innovative and affordable – it doesn’t get
                      better than Kalles. We are happy to introduce Kalles – The
                      BEST Shopify Theme!
                    </p>
                    <h2 class="mt-5">New filters has arrived</h2>
                    <v-divider></v-divider>

                    <img
                      src="https://camo.envatousercontent.com/3d6297e411b344aa1a182ddc57f7031918f37eb4/68747470733a2f2f7468656d65732e746865342e636f2f6b616c6c65732d6465732f6e65772d66696c7465722e676966"
                      alt="Kalles - Clean, Versatile, Responsive Shopify Theme - RTL support - 6"
                    />
                    <p>
                      - Regural agents can add and apply changes to their own
                      tenant.
                    </p>

                    <p>
                      - New Chrome extension to assist organizers of the
                      meetings. More information about this feature can be found
                      here.
                    </p>
                    <p>- Integration with DocTreat theme.</p>
                    <p>
                      - Video Session logs – gathering all video related events:
                      start video, end video, attendee joining and leaving,
                      start and stop screenshare, start and stop recording.
                    </p>
                    <p>- Added Terms & Conditions options in the Entry form.</p>
                    <p>
                      - Integration with latest WoWonder Social Network
                      Platform, WonderTag theme, PlayTube Platform and LatePoint
                      Plugin. You can read more about LiveSmart integrations
                      here.
                    </p>
                    <p>
                      - Picture in picture functionality. Picture-in-Picture
                      (PiP) allows your attendee video to be in a floating
                      window while you are on another tab or application.
                    </p>
                    <p>
                      - Social media login with Facebook and Google accounts.
                    </p>
                    <p>
                      - Added script and page to guide the customer through the
                      installation and setup process.
                    </p>
                    <p>
                      - Admission facility added. Host can approve or reject an
                      attendee in a meeting. If you need more information about
                      the features, have additional questions or difficulties
                      with the demos or installation, you can visit our support
                      forum
                    </p>
                    <h2>Super Fast Loading Speed:</h2>
                    <v-divider></v-divider>
                    <img
                      src="https://camo.envatousercontent.com/7c919a15242c5f1e7c67801ad8f2158bdfb2cf55/68747470733a2f2f7468656d65732e746865342e636f2f6b616c6c65732d6465732f7370656564312e706e67"
                      alt="fastest Shopify theme 2020"
                    />
                    <p>
                      Did you know that page load speed affects 70% of traffic?
                      Users will not stick around and buy if the speed is too
                      slow. With this in mind we have made Kalles one of our
                      fastest themes yet.
                    </p>

                    <h2 class="mt-3">Kalles 1.1 – Advance Product Type</h2>
                    <v-divider></v-divider>
                    <img
                      src="https://camo.envatousercontent.com/0fc9bbfa3fc3d7f27b5a552c90413c7397b2b2ee/68747470733a2f2f7468656d65732e746865342e636f2f6b616c6c65732d6465732f63686f6f73655f7374796c652e676966"
                      alt="Kalles - Clean, Versatile, Responsive Shopify Theme - RTL support - 7"
                    />
                    <p>
                      Features that are not yet available on any Shopify theme.
                      Inspired by dropship T-shirt stores, it makes it easy to
                      increase conversion rates by including related products.
                      Related products will also show this block, which is a
                      cross selling feature that helps you get the highest
                      conversion rates. You can check the demo HERE and this is
                    </p>
                    <nuxt-link to="#"><h1>DOCUMENT</h1></nuxt-link>
                    <img
                      src="https://camo.envatousercontent.com/dcd82522e21b0446dd54a72351f0b34b4968dd4a/68747470733a2f2f7468656d65732e746865342e636f2f6b616c6c65732d6465732f696e74726f2e6a7067"
                      alt="kalles shopify theme"
                    />

                    <h2 class="mt-3">Responsive and Retina-Ready Design</h2>
                    <v-divider></v-divider>

                    <img
                      src="https://camo.envatousercontent.com/25a78525b6ee3f15c8bc19668a8bddf5ef786d7c/68747470733a2f2f7468656d65732e746865342e636f2f6b616c6c65732d6465732f726573706f6e736976652d72657374696e612e706e67"
                      alt="Responsive Shopify Theme"
                    />
                    <p>
                      Whatever device your website is viewed on, kalles will
                      ensure your store looks and functions perfectly. This
                      includes meeting the parameters and dimensions of that
                      device without interrupting the user’s experience and
                      without needing any further input from you or your
                      developer.
                    </p>

                    <h2 class="mt-3">
                      Now, Kalles already supports video thumbnails and 3D
                    </h2>
                    <v-divider></v-divider>
                    <img
                      class="mt-3"
                      src="https://camo.envatousercontent.com/decc115016e51dfb314085796cd08dc5ac5c02c8/68747470733a2f2f7468656d65732e746865342e636f2f6b616c6c65732d6465732f766964656f2d33642e676966"
                      alt="Kalles - Clean, Versatile, Responsive Shopify Theme - RTL support - 8"
                    />
                    You can now use this official feature from Shopify on
                    Kalles. Currently, Kalles and Molla already support this
                    feature, we will update other items soon. You can learn
                    about this feature <nuxt-link to="#">HERE</nuxt-link>.

                    <h2 class="mt-3">Frequently Bought Together Built-in</h2>
                    <v-divider></v-divider>
                    <img
                      src="https://camo.envatousercontent.com/59efed9eee3f2657144b403788a7d8bf3464bd4e/68747470733a2f2f7468656d65732e746865342e636f2f6b616c6c65732d6465732f62756e646c652e706e67"
                      alt="product bundle Frequently Bought Together shopify"
                    />
                    <p>
                      The Frequently Bought Together built-in feature brings
                      this smart upsell feature into Shopify in the most
                      convenient way: you can have it ready in your store within
                      5 minutes with simple and easy configuration.
                    </p>
                    <h2 class="mt-3">
                      Plenty of Stunning Demos to choose from
                    </h2>
                    <v-divider></v-divider>
                    <img
                      src="https://camo.envatousercontent.com/f3ac21748476363acb4cc0544043141fcc6909cc/68747470733a2f2f7468656d65732e746865342e636f2f6b616c6c65732d6465732f64656d6f732e6a7067"
                      alt="Kalles supported 20+ awesome demos, the best Shopify theme"
                    />
                    <p>
                      The Frequently Bought Together built-in feature brings
                      this smart upsell feature into Shopify in the most
                      convenient way: you can have it ready in your store within
                      5 minutes with simple and easy configuration.
                    </p>

                    <h2 class="mt-3">Optimized Product Pages</h2>
                    <v-divider></v-divider>
                    <img
                      src="https://camo.envatousercontent.com/8906ca974974ff226f9b98259838182f37c45d55/68747470733a2f2f7468656d65732e746865342e636f2f6b616c6c65732d6465732f70726f647563742d6f7074696f6e73312e706e67"
                      alt="Kalles - Clean, Versatile, Responsive Shopify Theme - RTL support - 12"
                    />
                    <p>
                      Everything on the product page is optimized and
                      streamlined to bring the best experience to your
                      customers. It also has numerous components that help
                      increase conversion rates. Everything looks clean, tidy
                      and professional.
                    </p>
                    <img
                      src="https://camo.envatousercontent.com/aacaa9e5eb53e9cad87056f9263c889b5f1e0b98/68747470733a2f2f7468656d65732e746865342e636f2f6b616c6c65732d6465732f636f6c6f722d7377617463682e706e67"
                      alt="Kalles - Clean, Versatile, Responsive Shopify Theme - RTL support - 13"
                    />
                    <p>
                      Kalles also supports a variety of product variant
                      interfaces, allowing you to easily customize how they are
                      displayed on product pages, collection pages, home page,
                      etc.
                    </p>
                    <h1 class="mt-3">9+ Header Layouts</h1>
                    <v-divider></v-divider>
                    <img
                      src="https://camo.envatousercontent.com/7b626c6a75f9d55ad5c2d206cd2d174cc935342d/68747470733a2f2f7468656d65732e746865342e636f2f6b616c6c65732d6465732f6865616465722e706e67"
                      alt="Kalles - Clean, Versatile, Responsive Shopify Theme - RTL support - 14"
                    />
                    <p>
                      Kalles supports up to 9 Header options. Customers will
                      feel your shop is professional from the first second of
                      seeing the Header.
                    </p>

                    <h1 class="mt-3">Mobile Bottom Navigation</h1>
                    <img
                      src="https://camo.envatousercontent.com/d96adf16ed409151244c48f6b115c824d801cdaf/68747470733a2f2f7468656d65732e746865342e636f2f6b616c6c65732d6465732f6d6f62696c652d6261722e706e67"
                      alt="Kalles - Clean, Versatile, Responsive Shopify Theme - RTL support - 20"
                    />
                    <p>
                      This feature helps optimize the UI/UX in mobile, your
                      store looks like a mobile application and it is also very
                      smooth. With Kalles, everything is taken care of pixel by
                      pixel.
                    </p>
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
                              v-on="on"
                            >
                              Regular License <v-icon size="15" class="ml-2">mdi-arrow-down-drop-circle-outline</v-icon>
                            </v-btn>
                          </template>
                          <v-list>
                            <v-card flat width="350">
                              <p class="pl-5 d-inline">
                                Regular Lience
                                <v-btn class="primary" x-small>selected</v-btn>
                              </p>
                              <h4 class="d-inline float-right mr-3">$89</h4>
                              <p class="pl-5 mt-3 text--secondary">
                                Use, by you or one client, in a single end
                                product which end users are not charged for. The
                                total price includes the item price and a buyer
                                fee.
                              </p>
                            </v-card>
                            <v-divider class="mb-4"></v-divider>
                            <v-card flat width="350">
                              <p class="pl-5 d-inline">
                                Extended License
                                <v-btn class="primary" x-small>selected</v-btn>
                              </p>
                              <h4 class="d-inline float-right mr-3">$4750</h4>
                              <p class="pl-5 mt-3 text--secondary">
                                Use, by you or one client, in a single end
                                product which end users are not charged for. The
                                total price includes the item price and a buyer
                                fee.
                              </p>
                            </v-card>
                          </v-list>
                        </v-menu>
                      </div>
                      <div class="d-inline">
                        <h3 class="float-right">$89s</h3>
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
                        <div class="d-inline text-decoration-line-through">
                          $3500
                        </div>
                        <div class="d-inline">$1500</div>
                      </v-card>

                      <p class="font-italic text-caption my-3 ml-5 ">Price is in US dollars and excludes tax</p>
                      <v-btn class="success" block><v-icon size="18" class="pr-4">mdi-cart</v-icon> Add To cart</v-btn>
                    </v-card>
                  </v-col>
                </v-row>
              </v-card>
            </v-tab-item>
            <v-tab-item>
              <v-card flat>
                <IndividualItemDtails />
              </v-card>
            </v-tab-item>
            <v-tab-item>
              <v-card flat>
                <IndividualItemDtails />
              </v-card>
            </v-tab-item>
            <v-tab-item>
              <v-card flat>
                <IndividualItemDtails />
              </v-card>
            </v-tab-item>
          </v-tabs-items>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  data() {
    return {
      tab: null,
      items: ['web', 'shopping', 'videos', 'images', 'news'],
      text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.',
    }
  },
}
</script>