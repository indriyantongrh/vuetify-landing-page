<template>
  <v-footer dark padless>
    <div class="svg-border-waves text-white">
      <v-img src="~@/assets/img/borderWavesBlue.svg" />
    </div>
    <v-card flat tile class="secondary white--text ">
      <v-container>
        <v-layout row wrap justify-space-between text-xs-center class="mt-5">
          <v-flex xs10 sm3 text-xs-center>
            <img
              src="@/assets/img/logobni.png"
              class="elevation-1"
              style="max-width:150px;"
            />
            <!-- <p class="title mt-4">Vue-CLI Templates</p> -->
            <p>
              BNI Melayani Negeri, Kebanggaan Bangsa
            </p>
          </v-flex>
          <v-flex xs10 sm3 text-xs-center>
            <p class="title mt-4">BNI Divisi WHS</p>
            <p>
              Jl. Jendral Sudirman Kav 1 Gedung Grha BNI Lantai 23 Jakarta Pusat
              DKI Jakarta 1220
            </p>
          </v-flex>
          <v-flex xs10 sm3 text-xs-center>
            <p class="title mt-4">Hubungi Kami</p>
            <v-col>
              <img src="@/assets/img/message.png" style="max-width: 20px;" />
              <label> tbs_sat@bni.co.id</label>
            </v-col>
            <v-col class="mb-3">
              <img src="@/assets/img/phone-call.png" style="max-width: 20px;" />
              <label> 021 299 460 46</label>
            </v-col>
            <v-col>
              <img src="@/assets/img/whatsapp2.png" style="max-width: 20px;" />
              <label> +62 858 5000 1946</label>
            </v-col>
            <v-col>
              <img src="@/assets/img/telegram.png" style="max-width: 20px;" />
              <label> +62 858 5000 1946</label>
            </v-col>
          </v-flex>
          <v-flex xs10 sm3 text-xs-center>
            <p class="title mt-4">BNI Terdaftar & diawasi oleh:</p>
            <img
              src="@/assets/img/ojklps.png"
              class="elevation-1"
              style="max-width:350px;"
            />
          </v-flex>
        </v-layout>
        <!-- <v-row align="center" justify="center">
          <v-col cols="6" md="3">
            <v-card-text class="white--text pt-4 mx-12">
              <v-img src="@/assets/img/logobni.png" max-width="200px" />

              BNI Melayani Negeri, Kebanggaan Bangsa
            </v-card-text>
          </v-col>
          <v-col cols="6" md="3" class="d-none d-md-flex">
            <v-card-text class="white--text pt-4 mx-12">
              <h3 class=" mb-3">BNI Divisi WHS</h3>
              <p>
                Jl. Jendral Sudirman Kav 1 Gedung Grha BNI Lantai 23 Jakarta
                Pusat DKI Jakarta 1220
              </p>
            </v-card-text>
          </v-col>
          <v-col cols="6" md="3" class="d-none d-md-flex">
            <v-card-text class="white--text pt-4 mx-12">
              <h3 class=" mb-3">Hubungi Kami</h3>
              <p>
                Jl. Jendral Sudirman Kav 1 Gedung Grha BNI Lantai 23 Jakarta
                Pusat DKI Jakarta 1220
              </p>
            </v-card-text>
          </v-col>
          <v-col cols="6" md="3" class="d-none d-md-flex">
            <v-card-text class="white--text pt-4 mx-12">
              <v-img src="@/assets/img/logobni.png" max-width="200px" />

              BNI Melayani Negeri, Kebanggaan Bangsa
            </v-card-text>
          </v-col>
        </v-row> -->
      </v-container>

      <!-- 
      <v-card-text>
        <v-btn
          v-for="(icon, i) in icons"
          :key="i"
          class="mx-4 white--text"
          :href="icon.link"
          target="_blank"
          icon
        >
          <v-icon size="24px">{{ icon.text }}</v-icon>
        </v-btn>
      </v-card-text>

      <v-card-text class="white--text pt-0">
        Phasellus feugiat arcu sapien, et iaculis ipsum elementum sit amet.
        Mauris cursus commodo interdum.
      </v-card-text> -->

      <v-divider></v-divider>

      <v-card-text class="white--text">
        <span>© BNI Divisi WHS. All Rights Reserved,</span>
        {{ new Date().getFullYear() }} —
        <strong>PT. Bank Negara Indonesia .Tbk</strong>
      </v-card-text>
    </v-card>
  </v-footer>
</template>

<style scoped>
.v-card {
  width: 100%;
}
</style>

<script>
export default {
  data: () => ({
    icons: [
      {
        text: "mdi-facebook",
        link: "",
      },
      {
        text: "mdi-twitter",
        link: "",
      },
      {
        text: "mdi-linkedin",
        link: "",
      },
      {
        text: "mdi-instagram",
        link: "https://instagram.com/joabson_arley/",
      },
    ],
  }),
};
</script>
