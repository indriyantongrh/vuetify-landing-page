<template>
  <section class="pb-8" id="contact">
    <v-container fluid>
      <v-row align="center" justify="center">
        <v-col cols="10">
          <h1 class="font-weight-light orangebni--text">
            JASA & LAYANAN
          </h1>
          <h1 class="font-weight-bold display-2  mb-3">
            Produk Kami
          </h1>
          <carousel :autoplay="true" class="owl-item cloned">
            <!-- <template slot="prev"><span class="prev">prev</span></template> -->
            <!-- BNI Smart Commerce -->
            <v-card max-width="344">
              <v-img
                src="@/assets/img/SupplyChainFinancing.jpg"
                height="200px"
              ></v-img>

              <v-card-title>
                BNI Smart Commerce
              </v-card-title>

              <v-card-subtitle>
                Platform ekosistem atau komunitas bisnis untuk melaksanakan
                berbagai transaksi pembayaran jual-beli secara efektif dan
                efisien.
              </v-card-subtitle>

              <v-card-actions>
                <v-flex><smartcommerce /></v-flex>

                <v-spacer></v-spacer>
              </v-card-actions>
            </v-card>
            <!-- Ecosmart -->
            <v-card max-width="344">
              <v-img src="@/assets/img/Ecosmart.jpg" height="200px"></v-img>

              <v-card-title>
                BNI ECOSmart
              </v-card-title>

              <v-card-subtitle>
                merupakan solusi yang khusus dirancang untuk membantu nasabah
                perusahaan dalam melakukan aktivitas pengelolaan member untuk
                berbagai ecosystem secara optimal, efektif, efisien yang
                dilengkapi dengan berbagai fitur unggulan.
              </v-card-subtitle>

              <v-card-actions>
                <v-flex><ecosmart /></v-flex>

                <v-spacer></v-spacer>
              </v-card-actions>
            </v-card>
            <!-- BNI Smart City -->
            <v-card max-width="344">
              <v-img src="@/assets/img/smartcity.png" height="200px"></v-img>

              <v-card-title>
                BNI Smart City
              </v-card-title>

              <v-card-subtitle>
                Layanan perbankan unggulan berbasis digital dan infrastruktur
                yang handal serta dukungan berbagai jaringan dan channel untuk
                memberikan solusi bagi Pemerintah Daerah dalam mewujudkan Smart
                City
              </v-card-subtitle>

              <v-card-actions>
                <v-flex><smartcity /></v-flex>

                <v-spacer></v-spacer>
              </v-card-actions>
            </v-card>
            <!-- BNI Bank Guarantee -->
            <v-card max-width="344">
              <v-img src="@/assets/img/gebe.jpg" height="200px"></v-img>

              <v-card-title>
                Bank Guarantee
              </v-card-title>

              <v-card-subtitle>
                Pernyataan untuk menjamin pembayaran sejumlah uang kepada
                penerima jaminan, apabila pihak yang dijamin tidak dapat
                memenuhi kewajiban yang telah diperjanjikan.
              </v-card-subtitle>

              <v-card-actions>
                <v-flex><bankguarantee /></v-flex>

                <v-spacer></v-spacer>
              </v-card-actions>
            </v-card>
            <v-card max-width="344">
              <v-img src="@/assets/img/viac.jpg" height="200px"></v-img>

              <v-card-title>
                Virtual Account
              </v-card-title>

              <v-card-subtitle>
                Rekening virtual yang dibuka untuk mendukung pengelolaan
                transaksi penerimaan (collection) Perusahaan/Institusi agar
                berjalan efektif dan efisien.
              </v-card-subtitle>

              <v-card-actions>
                <v-btn color="orange lighten-2" text>
                  Selengkapnya
                </v-btn>

                <v-spacer></v-spacer>
              </v-card-actions>
            </v-card>
            <v-card max-width="344">
              <v-img src="@/assets/img/Supplychain.jpg" height="200px"></v-img>

              <v-card-title>
                Supply Chain Financing
              </v-card-title>

              <v-card-subtitle>
                Fasilitas berupa pengambilalihan tagihan kepada Korporat sebelum
                tanggal jatuh tempo untuk dibayarkan kepada Mitra Korporat
                (Supplier) dengan waktu lebih cepat.
              </v-card-subtitle>

              <v-card-actions>
                <v-btn color="orange lighten-2" text>
                  Selengkapnya
                </v-btn>

                <v-spacer></v-spacer>
              </v-card-actions>
            </v-card>
            <v-card max-width="344">
              <v-img
                src="@/assets/img/bnidirectgmbr.jpg"
                height="200px"
              ></v-img>

              <v-card-title>
                BNI Cash Management
              </v-card-title>

              <v-card-subtitle>
                Solusi pengelolaan arus kas perusahaan yang disesuaikan dengan
                kebutuhan nasabah.
              </v-card-subtitle>

              <v-card-actions>
                <v-btn color="orange lighten-2" text>
                  Selengkapnya
                </v-btn>

                <v-spacer></v-spacer>
              </v-card-actions>
            </v-card>
            <v-card max-width="344">
              <v-img src="@/assets/img/s2c.jpg" height="200px"></v-img>

              <v-card-title>
                Xpora
              </v-card-title>

              <v-card-subtitle>
                layanan komprehensif dari BNI untuk pelaku usaha di wilayah yang
                memiliki potensi UKM, dengan memberikan dukungan menyeluruh
                untuk memberikan akses permodalan.
              </v-card-subtitle>

              <v-card-actions>
                <v-btn color="orange lighten-2" text>
                  Selengkapnya
                </v-btn>

                <v-spacer></v-spacer>
              </v-card-actions>
            </v-card>
            <v-card max-width="344">
              <v-img
                src="@/assets/img/BNIFX-PageBanner.jpg"
                height="200px"
              ></v-img>

              <v-card-title>
                BNI FX
              </v-card-title>

              <v-card-subtitle>
                Platform digital berbasis web yang dapat diakses melalui
                jaringan internet oleh Nasabah Corporate untuk melakukan
                transaksi Valas non-fisik secara langsung dengan Dealer BNI
                Tresuri.
              </v-card-subtitle>

              <v-card-actions>
                <v-btn color="orange lighten-2" text>
                  Selengkapnya
                </v-btn>

                <v-spacer></v-spacer>
              </v-card-actions>
            </v-card>
            <v-card max-width="344">
              <v-img
                src="@/assets/img/BNIFX-PageBanner.jpg"
                height="200px"
              ></v-img>

              <v-card-title>
                BNI GIRO
              </v-card-title>

              <v-card-subtitle>
                Solusi pengelolaan arus kas perusahaan yang disesuaikan dengan
                kebutuhan nasabah.
              </v-card-subtitle>

              <v-card-actions>
                <v-btn color="orange lighten-2" text>
                  Selengkapnya
                </v-btn>

                <v-spacer></v-spacer>
              </v-card-actions>
            </v-card>
            <v-card max-width="344">
              <v-img src="@/assets/img/B2BSolutions.jpg" height="200px"></v-img>

              <v-card-title>
                B2B Connection
              </v-card-title>

              <v-card-subtitle>
                Solusi layanan perbankan secara Open Banking untuk sektor
                korporasi yang terintegrasi langsung dengan sistem API BNI.
              </v-card-subtitle>

              <v-card-actions>
                <v-btn color="orange lighten-2" text>
                  Selengkapnya
                </v-btn>

                <v-spacer></v-spacer>
              </v-card-actions>
            </v-card>
            <v-card max-width="344">
              <v-img src="@/assets/img/BTO.jpg" height="200px"></v-img>

              <v-card-title>
                BNI Trade Online
              </v-card-title>

              <v-card-subtitle>
                layanan Transaksi Trade menggunakan Sistem Aplikasi yang
                berbasis jaringan internet yang dapat digunakan Nasabah untuk
                mengajukan permohonan transaksi Trade maupun menerima hasil
                keputusan transaksi Trade dari Bank secara online.
              </v-card-subtitle>

              <v-card-actions>
                <v-btn color="orange lighten-2" text>
                  Selengkapnya
                </v-btn>

                <v-spacer></v-spacer>
              </v-card-actions>
            </v-card>
            <v-card max-width="344">
              <v-img src="@/assets/img/BTO.jpg" height="200px"></v-img>

              <v-card-title>
                BNI Trade Online
              </v-card-title>

              <v-card-subtitle>
                layanan Transaksi Trade menggunakan Sistem Aplikasi yang
                berbasis jaringan internet yang dapat digunakan Nasabah untuk
                mengajukan permohonan transaksi Trade maupun menerima hasil
                keputusan transaksi Trade dari Bank secara online.
              </v-card-subtitle>

              <v-card-actions>
                <v-btn color="orange lighten-2" text>
                  Selengkapnya
                </v-btn>

                <v-spacer></v-spacer>
              </v-card-actions>
            </v-card>
            <!-- <template slot="next"><span class="next">next</span></template> -->
          </carousel>
        </v-col>
      </v-row>
    </v-container>
    <div class="svg-border-waves text-white">
      <v-img src="~@/assets/img/borderWavesBlue.svg" />
    </div>
    <v-snackbar
      v-model="snackbar.enabled"
      timeout="3000"
      right
      top
      :color="snackbar.color"
    >
      {{ snackbar.text }}

      <template v-slot:action="{ attrs }">
        <v-btn text v-bind="attrs" @click="snackbar.enabled = false">
          Fechar
        </v-btn>
      </template>
    </v-snackbar>
  </section>
</template>

<style scoped>
#contact {
  background-color: #f4f7f5;
}

.svg-border-waves .v-image {
  position: absolute;
  bottom: 0;
  left: 0;
  height: 3rem;
  width: 100%;
  overflow: hidden;
}
</style>

<script>
// import {db} from '@/main'
import carousel from "vue-owl-carousel";
import smartcommerce from "../components/modal/modelsmartcommerce.vue";
import ecosmart from "../components/modal/modalecosmart.vue";
import smartcity from "../components/modal/modalsmartcity.vue";
import bankguarantee from "../components/modal/modalbankguarantee.vue";

export default {
  components: { carousel, smartcommerce, ecosmart, smartcity, bankguarantee },
  data: () => ({
    show: false,
    icons: ["fa-facebook", "fa-twitter", "fa-linkedin", "fa-instagram"],
    valid: true,
    name: "",
    nameRules: [
      (v) => !!v || "O campo nome é obrigatório",
      (v) => (v && v.length >= 6) || "O nome precisa ter mais de 6 caracteres",
    ],
    email: "",
    emailRules: [
      (v) => !!v || "O campo email é obrigatório",
      (v) => /.+@.+\..+/.test(v) || "O E-mail precisa ser válido",
    ],
    textArea: "",
    textAreaRules: [
      (v) => !!v || "O campo de texto é obrigatório",
      (v) => (v && v.length >= 10) || "Mínimo de 10 caracteres",
    ],
    lazy: false,
    snackbar: {
      enabled: false,
      text: "",
      color: "",
    },
  }),
  methods: {
    submit() {
      /*db.collection("contactData").add({
        name: this.name,
        email: this.email,
        message: this.textArea
      }).then(() => {
        this.snackbar.text = "Mensagem enviada com sucesso"
        this.snackbar.color = "success"
        this.snackbar.enabled = true
      }).catch(() => {
        this.snackbar.text = "Erro ao enviar mensagem"
        this.snackbar.color = "danger"
        this.snackbar.enabled = true
      })*/
    },
  },
};
</script>
