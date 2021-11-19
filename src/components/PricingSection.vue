<template>
  <section id="pricing" class="pb-8">
    <v-container fluid>
      <v-row align="center" justify="center">
        <v-col cols="10">
          <h1 class="font-weight-light orangebni--text">
            BNI UNTUK UMKM
          </h1>
          <h1 class="font-weight-bold display-2 black--text mb-6">
            Solusi BNI Mendukung UMKM Go Global
          </h1>
          <v-card style="width: 100% height: 100%">
            <v-row align="center" justify="center">
              <v-col cols="12" md="5" class="d-none d-md-flex">
                <v-img
                  src="@/assets/img/xpora.png"
                  class="d-block ml-auto mr-auto"
                  max-width="300px"
                />
              </v-col>
              <v-col cols="12" md="7">
                <v-row>
                  <v-col cols="12" class="d-flex align-center">
                    <v-col>
                      <h2>Ekspor Lebih Mudah</h2>
                      <p class="text-justify">
                        Tanpa batasan kini kita dapat menjelajahi pasar yang
                        lebih luas. Kami mendukung penuh kegiatan ekspor para
                        pebisnis Indonesia untuk lebih maju dan berkembang.
                        Temui lebih banyak kesempatan dan rekan bisnis yang
                        sesuai bagi anda dan bisnis anda. Dengan semangat yang
                        sama kami membantu para pebisnis memulai bisnis dan
                        berkembang mempersiapkan diri untuk menggapai kesempatan
                        yang lebih besar. Bersama Xpora, Ekspor lebih mudah.
                      </p>
                    </v-col>
                  </v-col>
                </v-row>
              </v-col>
            </v-row>
            <!-- <h1 class="text-center pt-6 font-weight-light display-2">Planos</h1> -->
            <v-divider class="my-6"></v-divider>

            <v-card class="margins" rounded="xl">
              <v-col cols="12 md-3">
                <v-row>
                  <v-col cols="12" class="d-flex align-center">
                    <v-col>
                      <h2>Ekspor Lebih Mudah</h2>
                      <p class="text-justify">
                        Tanpa batasan kini kita dapat menjelajahi pasar yang
                        lebih luas. Kami mendukung penuh kegiatan ekspor para
                        pebisnis Indonesia untuk lebih maju dan berkembang.
                        Temui lebih banyak kesempatan dan rekan bisnis yang
                        sesuai bagi anda dan bisnis anda. Dengan semangat yang
                        sama kami membantu para pebisnis memulai bisnis dan
                        berkembang mempersiapkan diri untuk menggapai kesempatan
                        yang lebih besar. Bersama Xpora, Ekspor lebih mudah.
                      </p>
                    </v-col>
                  </v-col>
                </v-row>
              </v-col>
              <h3 class="ma-8  mb-3">Explore Our Features :</h3>

              <v-dialog transition="dialog-top-transition" max-width="600">
                <template v-slot:activator="{ on, attrs }">
                  <v-btn
                    v-bind="attrs"
                    v-on="on"
                    elevation="2"
                    rounded
                    large
                    color="orangebni white--text"
                    class="mt-6 ma-8"
                  >
                    <v-img src="@/assets/img/bc.png" max-width="25px" />Bisnis
                    Checkup</v-btn
                  >
                </template>
                <template v-slot:default="dialog">
                  <v-card>
                    <v-toolbar color="hijaubni" dark
                      ><v-img
                        src="@/assets/img/bc.png"
                        max-width="25px"
                      />Bisnis Checkup</v-toolbar
                    >
                    <v-card-text>
                      <v-col cols="12" class="d-flex align-center">
                        <v-col>
                          <p class="text-justify">
                            Kami menghadirkan berbagai informasi, pengetahuan,
                            dan kesempatan layanan yang dibutuhkan bisnis Anda.
                          </p>
                        </v-col>
                      </v-col>
                      <v-btn
                        elevation="2"
                        rounded
                        large
                        color="orangebni white--text"
                        @click="klikcekBC()"
                      >
                        Cek Sekarang
                      </v-btn>
                      <v-btn
                        elevation="2"
                        rounded
                        large
                        color="orangebni white--text"
                        @click="newbisnisBC()"
                      >
                        Belum punya bisnis
                      </v-btn>
                    </v-card-text>
                    <v-card-actions class="justify-end">
                      <v-btn text @click="dialog.value = false">Close</v-btn>
                    </v-card-actions>
                  </v-card>
                </template>
              </v-dialog>

              <v-dialog transition="dialog-top-transition" max-width="600">
                <template v-slot:activator="{ on, attrs }">
                  <v-btn
                    elevation="2"
                    rounded
                    large
                    v-bind="attrs"
                    v-on="on"
                    color="orangebni white--text"
                    class="mt-6 ma-8"
                  >
                    <v-img src="@/assets/img/em.png" max-width="25px" />Expansi
                    Market</v-btn
                  >
                </template>
                <template v-slot:default="dialog">
                  <v-card>
                    <v-toolbar color="hijaubni" dark
                      ><v-img
                        src="@/assets/img/em.png"
                        max-width="25px"
                      />Expansi Market</v-toolbar
                    >
                    <v-card-text>
                      <v-col cols="12" class="d-flex align-center">
                        <v-col>
                          <p class="text-justify">
                            KDengan berbagai macam market tersedia lokal maupun
                            internasional kami dapat mempertemukan kedua pelaku
                            usaha agar bisnis semakin berkembang.
                          </p>
                        </v-col>
                      </v-col>
                      <v-btn
                        elevation="2"
                        rounded
                        large
                        color="orangebni white--text"
                        @click="market()"
                      >
                        Cari Market Baru
                      </v-btn>
                    </v-card-text>
                    <v-card-actions class="justify-end">
                      <v-btn text @click="dialog.value = false">Close</v-btn>
                    </v-card-actions>
                  </v-card>
                </template>
              </v-dialog>

              <v-dialog transition="dialog-top-transition" max-width="600">
                <template v-slot:activator="{ on, attrs }">
                  <v-btn
                    elevation="2"
                    rounded
                    large
                    v-bind="attrs"
                    v-on="on"
                    color="orangebni white--text"
                    class="mt-6 ma-8"
                  >
                    <v-img src="@/assets/img/st.png" max-width="25px" />SME
                    Tools</v-btn
                  >
                </template>
                <template v-slot:default="dialog">
                  <v-card>
                    <v-toolbar color="hijaubni" dark
                      ><v-img src="@/assets/img/st.png" max-width="25px" />SME
                      Tools</v-toolbar
                    >
                    <v-card-text>
                      <v-col cols="12" class="d-flex align-center">
                        <v-col>
                          <p class="text-justify">
                            Kami berusaha memetakan tools untuk UMKM agar tools
                            yang dibutuhkan mudah dicari sesuai dengan
                            kebutuhannya, juga kami mengintegrasikan tools yang
                            ada dengan kebutuhan bisnis anda.
                          </p>
                        </v-col>
                      </v-col>
                      <v-btn
                        elevation="2"
                        rounded
                        large
                        color="orangebni white--text"
                        @click="smetools()"
                      >
                        Cari Tools
                      </v-btn>
                    </v-card-text>
                    <v-card-actions class="justify-end">
                      <v-btn text @click="dialog.value = false">Close</v-btn>
                    </v-card-actions>
                  </v-card>
                </template>
              </v-dialog>

              <v-dialog transition="dialog-top-transition" max-width="600">
                <template v-slot:activator="{ on, attrs }">
                  <v-btn
                    elevation="2"
                    rounded
                    large
                    v-bind="attrs"
                    v-on="on"
                    color="orangebni white--text"
                    class="mt-6 ma-8"
                  >
                    <v-img
                      src="@/assets/img/inspirasi.png"
                      max-width="25px"
                    />Inspirasi
                  </v-btn>
                </template>
                <template v-slot:default="dialog">
                  <v-card>
                    <v-toolbar color="hijaubni" dark>
                      <v-img
                        src="@/assets/img/inspirasi.png"
                        max-width="25px"
                      />
                      <label>Inspirasi</label></v-toolbar
                    >
                    <v-card-text>
                      <v-col cols="12" class="d-flex align-center">
                        <v-col>
                          <p class="text-justify">
                            Kami menyajikan banyak inspirasi berupa video,
                            artikel dan event yang pasti sangat relevan untuk
                            setiap segmen bisnis guna menambah pengetahuan
                            terhadap sektor yang dihadapi.
                          </p>
                        </v-col>
                      </v-col>
                      <v-btn
                        elevation="2"
                        rounded
                        large
                        color="orangebni white--text"
                        @click="inspirasi()"
                      >
                        Jelajahi Inspirasi
                      </v-btn>
                    </v-card-text>
                    <v-card-actions class="justify-end">
                      <v-btn text @click="dialog.value = false">Close</v-btn>
                    </v-card-actions>
                  </v-card>
                </template>
              </v-dialog>
              <!-- Tab navogation -->
              <!-- <v-col cols="12">
                <v-card class="transparent">
                  <v-tabs v-model="tab2" centered class="tab-index">
                    <v-tab v-for="item in items" :key="item">
                      {{ item.title }}
                    </v-tab>
                  </v-tabs>

                  <v-tabs-items v-model="tab2">
                    <v-tab-item
                      v-for="item in items"
                      :key="item"
                      class="text-center mt-2"
                    >
                      <v-card-title class="d-flex justify-center">
                        Navigation Card
                      </v-card-title>
                      <v-card-text v-text="text"></v-card-text>

                      <v-card-text>
                        <v-btn color="primary">
                          Learn More
                        </v-btn>
                      </v-card-text>
                    </v-tab-item>
                  </v-tabs-items>
                </v-card>
              </v-col> -->
            </v-card>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
    <div class="svg-border-rounded text-light">
      <!-- <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 144.54 17.34"
        preserveAspectRatio="none"
        fill="currentColor"
      >
        <path
          d="M144.54,17.34H0V0H144.54ZM0,0S32.36,17.34,72.27,17.34,144.54,0,144.54,0"
        />
      </svg> -->
      <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 1440 320"
        preserveAspectRatio="none"
        fill="currentColor"
      >
        <path
          d="M0,64L80,90.7C160,117,320,171,480,181.3C640,192,800,160,960,138.7C1120,117,1280,107,1360,101.3L1440,96L1440,320L1360,320C1280,320,1120,320,960,320C800,320,640,320,480,320C320,320,160,320,80,320L0,320Z"
        ></path>
      </svg>
    </div>
  </section>
</template>

<style lang="scss">
$main_color: #283e79;

ul {
  font-size: 13px;
  line-height: 1.5em;
  margin: 5px 0 15px;
  padding: 0;

  li {
    list-style: none;
    position: relative;
    padding: 0 0 0 20px;
  }

  li {
    &::before {
      content: "";
      position: absolute;
      left: 0;
      top: 5px;
      width: 10px;
      height: 10px;
      background-color: $main_color;
      border-radius: 50%;
      -moz-border-radius: 50%;
      -webkit-eeborder-radius: 50%;
    }
  }
}
</style>

<style scoped>
.header {
  background-color: #283e79;
  color: white;
}

.circle1 {
  border-radius: 50%;
  width: 150px;
  height: 150px;
  background-color: #f0f8ff;
  display: flex;
  align-items: center;
  justify-content: center;
}

.circle2 {
  border-radius: 50%;
  width: 100px;
  height: 100px;
  background-color: #e0effc;
  display: flex;
  align-items: center;
  justify-content: center;
}

.flex-center {
  display: flex;
  align-items: center;
  justify-content: center;
}

.svg-border-rounded svg {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  color: #f4f7f5;
  z-index: -1;
}

#pricing {
  z-index: 0;
}

.content {
  z-index: 1;
}

svg {
  overflow: hidden;
}

section {
  position: relative;
}
</style>

<script>
export default {
  data: () => ({
    tab2: null,
    items: [
      { title: "Bisnis Checkup" },
      { title: "Expansi Market" },
      { title: "SME Tools" },
      { title: "Inspirasi" },
    ],
    text:
      "Although cards can support multiple actions, UI controls, and an overflow menu, use restraint and remember that cards…",

    planos: [
      {
        title: "Básico",
        price: "R$100,00",
        img: "f1.png",
        features: [
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 1",
          },
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 2",
          },
          {
            icon: {
              text: "mdi-cancel",
              color: "red",
            },
            text: "Feature 3",
          },
          {
            icon: {
              text: "mdi-cancel",
              color: "red",
            },
            text: "Feature 4",
          },
        ],
      },
      {
        title: "Padrão",
        price: "R$150,00",
        img: "f2.png",
        features: [
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 1",
            color: "success",
          },
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 2",
          },
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 3",
            color: "success",
          },
          {
            icon: {
              text: "mdi-cancel",
              color: "red",
            },
            text: "Feature 4",
          },
        ],
      },
      {
        title: "Premium",
        price: "R$250,00",
        img: "f3.png",
        features: [
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 1",
            color: "success",
          },
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 2",
          },
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 3",
            color: "success",
          },
          {
            icon: {
              text: "mdi-check",
              color: "success",
            },
            text: "Feature 4",
            color: "success",
          },
        ],
      },
    ],
  }),
  computed: {
    size() {
      const size = { md: "large", xl: "x-large" }[
        this.$vuetify.breakpoint.name
      ];
      return size ? { [size]: true } : {};
    },
  },
  methods: {
    async klikcekBC() {
      window.open("https://xpora.bni.co.id/business-checkup", "_blank");
    },
    async newbisnisBC() {
      window.open(
        "https://xpora.bni.co.id/business-checkup/new-business",
        "_blank"
      );
    },
    async market() {
      window.open("https://xpora.bni.co.id/market", "_blank");
    },
    async smetools() {
      window.open("https://xpora.bni.co.id/sme-tools", "_blank");
    },
    async inspirasi() {
      window.open("https://xpora.bni.co.id/inspire", "_blank");
    },
  },
};
</script>

<style lang="scss" scoped>
.tab-index {
  position: relative;
  z-index: 1;
}
.transparent {
  background-color: white !important;
  opacity: 0.65;
  border-color: transparent !important;
}
.cardwidth {
  min-width: 100px;
  padding: 30px;
}
.rounded-card {
  border-radius: 30px;
}
.margins {
  margin-left: 30px !important;
  margin-right: 30px !important;
}
</style>
