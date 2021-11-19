<template>
  <section id="download">
    <v-container fluid class="mt-2">
      <v-col cols="12" md="12" padding="30"> </v-col>
      <v-row align="center" justify="center">
        <v-col cols="10">
          <h1 class="font-weight-light orangebni--text">
            MENGAPA HARUS MEMILIH BNI CASH MANAGEMENT?
          </h1>
          <h1 class="font-weight-bold display-2 white--text mb-3">
            Keunggulan
          </h1>
          <v-row align="center" justify="space-around">
            <!-- <v-col cols="12" class="text-center">
              <h1 class="font-weight-light display-2">Title</h1>
              <h1 class="font-weight-light">
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
              </h1>
            </v-col> -->
            <v-col
              cols="12"
              sm="4"
              class="text-center"
              v-for="(feature, i) in features"
              :key="i"
            >
              <v-hover v-slot:default="{ hover }">
                <v-card
                  class="card"
                  shaped
                  :elevation="hover ? 10 : 4"
                  :class="{ up: hover }"
                >
                  <v-img
                    :src="feature.img"
                    max-width="70px"
                    class="d-block ml-auto mr-auto"
                    :class="{ 'zoom-efect': hover }"
                  ></v-img>
                  <h1 class="font-weight-regular subtitle-1">
                    {{ feature.title }}
                  </h1>
                  <h4 class="font-weight-light subtitle-2">
                    {{ feature.text }}
                  </h4>
                </v-card>
              </v-hover>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>

<script>
export default {
  data() {
    return {
      dialog: false,
      videoId: "i8IvvHJssWE",
      features: [
        {
          img: require("@/assets/img/24-hours.png"),
          title: "Transaksi Real Time Online 24/7",
          text:
            "Customer anda dapat melakukan transaksi pembayaran kapanpun (24/7).",
        },
        {
          img: require("@/assets/img/fast.png"),
          title: "Pelayanan responsif dan solutif",
          text:
            "Tim kami dengan siaga akan menjawab pertanyaan terkait handling complain.",
        },
        {
          img: require("@/assets/img/statistics.png"),
          title: "Integrasi sistem yang mudah dan cepat",
          text:
            "Implementasi mudah dan cepat dengan beberapa pilihan skema integrasi yang disesuaikan dengan kebutuhan bisnis Anda.",
        },
        {
          img: require("@/assets/img/education.png"),
          title: "Solusi yang customized dan inovatif",
          text:
            "Memberikan solusi-solusi digital yang inovatif dan sesuai dengan kebutuhan nasabah.",
        },
        {
          img: require("@/assets/img/network.png"),
          title: "Jaringan dan ekosistem bisnis skala internasional",
          text:
            "Memudahkan nasabah dalam melakukan bisnis skala internasional dengan jaringan dan ekosistem BNI yang luas dan terdapat di berbagai negara.",
        },
        {
          img: require("@/assets/img/interactive.png"),
          title: "Fleksibilitas Channel Pembayaran",
          text:
            "Kemudahan pembayaran tagihan oleh customer Anda di seluruh channel Bank di Indonesia.",
        },
      ],
    };
  },
  watch: {
    dialog(value) {
      if (!value) {
        this.pause();
      }
    },
  },
  methods: {
    ready(event) {
      this.player = event.target;
    },
    playing(event) {
      // The player is playing a video.
    },
    change() {
      // when you change the value, the player will also change.
      // If you would like to change `playerVars`, please change it before you change `videoId`.
      // If `playerVars.autoplay` is 1, `loadVideoById` will be called.
      // If `playerVars.autoplay` is 0, `cueVideoById` will be called.
      this.videoId = "another video id";
    },
    stop() {
      this.player.stopVideo();
    },
    pause() {
      this.player.pauseVideo();
    },
  },
};
</script>
<style scoped>
#download {
  background-image: url("~@/assets/img/bgDownload.jpg");
  background-attachment: fixed;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  height: auto;
  padding: 30px;
}

#download .container,
#download .row {
  height: 100%;
}
</style>

<style>
.btn-play {
  transition: 0.2s;
}

.svg-border-waves .v-image {
  position: absolute;
  bottom: 0;
  left: 0;
  height: 3rem;
  width: 100%;
  overflow: hidden;
}

#hero {
  z-index: 0;
}
.svg-border-waves img {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  margin-bottom: -2px;
  z-index: -1;
}

.card {
  min-height: 300px;
  padding: 10px;
  transition: 0.5s ease-out;
}

.card .v-image {
  margin-bottom: 15px;
  transition: 0.75s;
}

.card h1 {
  margin-bottom: 10px;
}

.zoom-efect {
  transform: scale(1.1);
}

.up {
  transform: translateY(-20px);
  transition: 0.5s ease-out;
}
</style>

<style>
section {
  position: relative;
}
</style>
