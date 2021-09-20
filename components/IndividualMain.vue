<template>
  <v-container>
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

        <v-card dense tile flat>
          <v-tabs v-model="tab" align-with-title>
            <v-tabs-slider color="grey"></v-tabs-slider>

            <v-tab dense tile class="text-capitalize text-caption">
              Item Details
            </v-tab>
            <v-tab class="text-capitalize text-caption"> Reviews </v-tab>
            <v-tab class="text-capitalize text-caption"> Comments </v-tab>
            <v-tab class="text-capitalize text-caption"> Supports </v-tab>
          </v-tabs>

          <v-tabs-items v-model="tab">
            <v-tab-item>
             <IndividualItemDtails />
            </v-tab-item>
            <v-tab-item>
              <v-card flat tile>
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
  data: () => ({
    rating: 4.3,
    // main tab declaration here//
    tab: null,
  }),
}
</script>

