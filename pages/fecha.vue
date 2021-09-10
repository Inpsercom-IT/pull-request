<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="12" md="12">
      <v-footer
        color="primary lighten-1"
        padless
      >
        <v-row
          justify="center"
          no-gutters
        >
          <v-col
            class="primary lighten-2 py-4 text-center white--text"
            cols="12"
          >
            {{ new Date().getFullYear() }} — <strong>FECHA_CREACION</strong>
          </v-col>
          <v-col
            class="primary lighten-2 py-4 text-center white--text"
            cols="12"
          >
            {{ new Date().getFullYear() }} — <strong>FECHA_MODIFICACION</strong>
          </v-col>
        </v-row>
      </v-footer>
    </v-col>
  </v-row>
</template>
<script>
export default {
  data: () => ({
    links: [
      'FECHA_CREACION',
      'FECHA_MODIFICACION'
    ],
  }),
}
</script>
