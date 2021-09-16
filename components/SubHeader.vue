<template>
  <v-row>
  <v-col cols="12" sm="12" md="12">
      <v-menu open-on-hover down offset-y>
        <template #activator="{ on, attrs }">
          <v-btn
            tile
            text
            class="text-capitalize text--secondary caption ml-n3"
            v-bind="attrs"
            v-on="on"
          >
            All Items
          </v-btn>
        </template>
        <v-list>
          <v-list-item><Nuxt-link  class="text-capitalize text--secondary caption text-decoration-none" to="#"> Popular Files </Nuxt-link></v-list-item>
          <v-list-item><Nuxt-link  class="text-capitalize text--secondary caption text-decoration-none" to="#">Feature Files</Nuxt-link>  </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top New FIles</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Follow Feed</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top Authors</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top New Authors</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Public Collection</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">View All Categories</Nuxt-link> </v-list-item>
        </v-list>
      </v-menu>
     
      <v-menu open-on-hover down offset-y>
        <template #activator="{ on, attrs }">
          <v-btn
            tile
            text
            class="text-capitalize text--secondary caption ml-n5"
            v-bind="attrs"
            v-on="on"
          >
            Wordpress
          </v-btn>
        </template>

        <v-list>
          <v-list-item><Nuxt-link  class="text-capitalize text--secondary caption text-decoration-none" to="#"> Popular Files </Nuxt-link></v-list-item>
          <v-list-item><Nuxt-link  class="text-capitalize text--secondary caption text-decoration-none" to="#">Feature Files</Nuxt-link>  </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top New FIles</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Follow Feed</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top Authors</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top New Authors</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Public Collection</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">View All Categories</Nuxt-link> </v-list-item>
        </v-list>
      </v-menu>
     
      <v-menu open-on-hover down offset-y>
        <template #activator="{ on, attrs }">
          <v-btn
            tile
            text
            class="text-capitalize text--secondary caption ml-n5"
            v-bind="attrs"
            v-on="on"
          >
            Elementor
          </v-btn>
        </template>

        <v-list>
         <v-list-item  class="text-capitalize text--secondary caption"><Nuxt-link to="#"> Template Kits </Nuxt-link></v-list-item>
          <v-list-item  class="text-capitalize text--secondary caption"><Nuxt-link to="#">Plugins</Nuxt-link>  </v-list-item>
          <v-list-item  class="text-capitalize text--secondary caption"> <Nuxt-link to="#">Themes</Nuxt-link> </v-list-item>
        </v-list>
      </v-menu>
     
      <v-menu open-on-hover down offset-y>
        <template #activator="{ on, attrs }">
          <v-btn
            tile
            text
            class="text-capitalize text--secondary caption ml-n5"
            v-bind="attrs"
            v-on="on"
          >
            Hosting
          </v-btn>
        </template>

        <v-list>
         <v-list-item><Nuxt-link  class="text-capitalize text--secondary caption text-decoration-none" to="#"> Popular Files </Nuxt-link></v-list-item>
          <v-list-item><Nuxt-link  class="text-capitalize text--secondary caption text-decoration-none" to="#">Feature Files</Nuxt-link>  </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top New FIles</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Follow Feed</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top Authors</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top New Authors</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Public Collection</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">View All Categories</Nuxt-link> </v-list-item>
        </v-list>
      </v-menu>
     
      <v-menu open-on-hover down offset-y>
        <template #activator="{ on, attrs }">
          <v-btn
            tile
            text
            class="text-capitalize text--secondary caption ml-n5"
            v-bind="attrs"
            v-on="on"
          >
            HTML
          </v-btn>
        </template>

        <v-list>
         <v-list-item><Nuxt-link  class="text-capitalize text--secondary caption text-decoration-none" to="#"> Popular Files </Nuxt-link></v-list-item>
          <v-list-item><Nuxt-link  class="text-capitalize text--secondary caption text-decoration-none" to="#">Feature Files</Nuxt-link>  </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top New FIles</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Follow Feed</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top Authors</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top New Authors</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Public Collection</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">View All Categories</Nuxt-link> </v-list-item>
        </v-list>
      </v-menu>
      
      <v-menu open-on-hover down offset-y>
        <template #activator="{ on, attrs }">
          <v-btn
            tile
            text
            class="text-capitalize text--secondary caption ml-n5"
            v-bind="attrs"
            v-on="on"
          >
            Marketing
          </v-btn>
        </template>

        <v-list>
          <v-list-item><Nuxt-link  class="text-capitalize text--secondary caption text-decoration-none" to="#"> Popular Files </Nuxt-link></v-list-item>
          <v-list-item><Nuxt-link  class="text-capitalize text--secondary caption text-decoration-none" to="#">Feature Files</Nuxt-link>  </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top New FIles</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Follow Feed</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top Authors</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top New Authors</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Public Collection</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">View All Categories</Nuxt-link> </v-list-item>
        </v-list>
      </v-menu>
      
      <v-menu open-on-hover down offset-y>
        <template #activator="{ on, attrs }">
          <v-btn
            tile
            text
            class="text-capitalize text--secondary caption ml-n5"
            v-bind="attrs"
            v-on="on"
          >
            CMS
          </v-btn>
        </template>

        <v-list>
           <v-list-item><Nuxt-link  class="text-capitalize text--secondary caption text-decoration-none" to="#"> Popular Files </Nuxt-link></v-list-item>
          <v-list-item><Nuxt-link  class="text-capitalize text--secondary caption text-decoration-none" to="#">Feature Files</Nuxt-link>  </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top New FIles</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Follow Feed</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top Authors</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top New Authors</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Public Collection</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">View All Categories</Nuxt-link> </v-list-item>
        </v-list>
      </v-menu>
    
      <v-menu open-on-hover down offset-y>
        <template #activator="{ on, attrs }">
          <v-btn
            tile
            text
            class="text-capitalize text--secondary caption ml-n5"
            v-bind="attrs"
            v-on="on"
          >
            eCommerce
          </v-btn>
        </template>

        <v-list>
        <v-list-item><Nuxt-link  class="text-capitalize text--secondary caption text-decoration-none" to="#"> Popular Files </Nuxt-link></v-list-item>
          <v-list-item><Nuxt-link  class="text-capitalize text--secondary caption text-decoration-none" to="#">Feature Files</Nuxt-link>  </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top New FIles</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Follow Feed</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top Authors</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top New Authors</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Public Collection</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">View All Categories</Nuxt-link> </v-list-item>
        </v-list>
      </v-menu>
      
      <v-menu open-on-hover down offset-y>
        <template #activator="{ on, attrs }">
          <v-btn
            tile
            text
            class="text-capitalize text--secondary caption ml-n5"
            v-bind="attrs"
            v-on="on"
          >
            UI Templates
          </v-btn>
        </template>

        <v-list>
         <v-list-item><Nuxt-link  class="text-capitalize text--secondary caption text-decoration-none" to="#"> Popular Files </Nuxt-link></v-list-item>
          <v-list-item><Nuxt-link  class="text-capitalize text--secondary caption text-decoration-none" to="#">Feature Files</Nuxt-link>  </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top New FIles</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Follow Feed</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top Authors</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top New Authors</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Public Collection</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">View All Categories</Nuxt-link> </v-list-item>
        </v-list>
      </v-menu>
      
      <v-menu open-on-hover down offset-y>
        <template #activator="{ on, attrs }">
          <v-btn
            tile
            text
            class="text-capitalize text--secondary caption ml-n5"
            v-bind="attrs"
            v-on="on"
          >
            Plugins
          </v-btn>
        </template>

        <v-list>
    <v-list-item><Nuxt-link  class="text-capitalize text--secondary caption text-decoration-none" to="#"> Popular Files </Nuxt-link></v-list-item>
          <v-list-item><Nuxt-link  class="text-capitalize text--secondary caption text-decoration-none" to="#">Feature Files</Nuxt-link>  </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top New FIles</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Follow Feed</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top Authors</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top New Authors</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Public Collection</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">View All Categories</Nuxt-link> </v-list-item>
        </v-list>
      </v-menu>
     
      <v-menu open-on-hover down offset-y>
        <template #activator="{ on, attrs }">
          <v-btn
            tile
            text
            class="text-capitalize text--secondary caption ml-n5"
            v-bind="attrs"
            v-on="on"
          >
            Logo Maker <v-icon class="pl-1" size="12">mdi-launch</v-icon>
          </v-btn>
        </template>

        <v-list>
         <v-list-item><Nuxt-link  class="text-capitalize text--secondary caption text-decoration-none" to="#"> Popular Files </Nuxt-link></v-list-item>
          <v-list-item><Nuxt-link  class="text-capitalize text--secondary caption text-decoration-none" to="#">Feature Files</Nuxt-link>  </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top New FIles</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Follow Feed</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top Authors</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top New Authors</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Public Collection</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">View All Categories</Nuxt-link> </v-list-item>
        </v-list>
      </v-menu>
     
      <v-menu open-on-hover down offset-y>
        <template #activator="{ on, attrs }">
          <v-btn
            tile
            text
            class="text-capitalize text--secondary caption ml-n5"
            v-bind="attrs"
            v-on="on"
          >
            More
          </v-btn>
        </template>

        <v-list>
        <v-list-item><Nuxt-link  class="text-capitalize text--secondary caption text-decoration-none" to="#"> Popular Files </Nuxt-link></v-list-item>
          <v-list-item><Nuxt-link  class="text-capitalize text--secondary caption text-decoration-none" to="#">Feature Files</Nuxt-link>  </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top New FIles</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Follow Feed</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top Authors</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Top New Authors</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">Public Collection</Nuxt-link> </v-list-item>
          <v-list-item><Nuxt-link class="text-capitalize text--secondary caption text-decoration-none" to="#">View All Categories</Nuxt-link> </v-list-item>
        </v-list>
      </v-menu>
     
    <v-divider></v-divider>
  
  </v-col>
  </v-row>

</template>



