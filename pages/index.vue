<template>
  <v-layout
    column
    justify-center
    align-center
  >
    <v-flex
      xs12
      sm8
      md6
    >
      <div class="text-center">
        <!--logo />
        <vuetify-logo /-->
		HolyWheelin'
      </div>

      <v-card>
        <v-card-title class="headline">
          v-card テスト
        </v-card-title>
        <v-card-text>
          <p>テスト</p>
          <div class="text-xs-right">
            <em><small>&mdash; 主催者</small></em>
          </div>
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn
            color="primary"
            nuxt
            to="/inspire"
          >
            Continue
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
//import Logo from '~/components/Logo.vue'
//import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    //Logo,
    //VuetifyLogo
  }
}
</script>
