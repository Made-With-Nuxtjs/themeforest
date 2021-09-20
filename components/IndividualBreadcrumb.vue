<template>
  <v-container>
    <v-row no-gutters class="mt-n5">
      <v-col
        md="10"
        offset-md="1"
      >
        <v-breadcrumbs :items="items">
      <template #divider>
        <v-icon>mdi-chevron-right</v-icon>
      </template>
    </v-breadcrumbs>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
  export default {
    data: () => ({
      items: [
        {
          text: 'Home',
          disabled: false,
          href: '/',
        },
        {
          text: 'Files',
          disabled: true,
          href: 'breadcrumbs_link_1',
        },
        {
          text: 'eCommerce',
          disabled: true,
          href: 'breadcrumbs_link_2',
        },
        {
          text: 'Shopify',
          disabled: true,
          href: 'breadcrumbs_link_2',
        },
        {
          text: 'Fashion',
          disabled: true,
          href: 'breadcrumbs_link_2',
        },
      ],
    }),
  }
</script>