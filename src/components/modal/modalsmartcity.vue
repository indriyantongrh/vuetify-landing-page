<template>
  <v-dialog
    v-model="dialog"
    scrollable
    transition="dialog-top-transition"
    max-width="1000"
  >
    <template v-slot:activator="{ on, attrs }">
      <v-btn color="orange lighten-2" v-bind="attrs" v-on="on" text>
        Selengkapnya
      </v-btn>
    </template>
    <v-card>
      <v-toolbar color="hijaubni" dark>BNI Smart City </v-toolbar>

      <v-card-text>
        <v-col cols="12" class="d-flex align-center">
          <v-col>
            <v-card-text>
              <!-- <v-img src="@/assets/img/ecommerce.jpg" max-width="250px" /> -->

              <div>
                <b> BNI Smart City </b> merupakan kota/kabupaten yang telah
                mengintegrasikan teknologi informasi dan komunikasi dalam tata
                kelola sehari-hari dengan tujuan untuk mempertinggi efisiensi,
                memperbaiki pelayanan publik, dan meningkatkan kesejahteraan
                warga. Melalui kosep smart city yang diberikan BNI, yaitu Smart
                Environtment, Smart People, Smart Economy, Smart Governance,
                Smart Society, dan Smart Infrastructure.
              </div>
              <br />

              <v-col>
                <v-row>
                  <v-img src="@/assets/img/medal.png" max-width="20px" />
                  <b>Smart Environment</b>
                </v-row>
                <v-row>
                  <label>
                    Merupakan pengelolaan lingkungan yang seimbang antara
                    pembangunan infrastruktur fisik dengan sarana dan prasarana
                    warga, misalnya pengelolaan energi, sampah dan perlindungan
                    lingkungan.</label
                  >
                </v-row>
              </v-col>
              <br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/medal.png" max-width="20px" />
                  <b>Smart People</b>
                </v-row>
                <v-row>
                  <label>
                    Membentuk masyarakat menjadi well educated dan well behavior
                    melalui mekanisme perubahan teknologi dan tata Kelola</label
                  >
                </v-row>
              </v-col>
              <br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/medal.png" max-width="20px" />
                  <b> Smart Economy</b>
                </v-row>
                <v-row>
                  <label>
                    Ekosistem yang mendukung aktifitas ekonomi masyarakat,
                    dengan transaksi cashless. Melalui BNI Virtual Account &
                    eCollection, BNI Garansi Bank & FSCM</label
                  >
                </v-row>
              </v-col>
              <br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/medal.png" max-width="20px" />
                  <b> Smart Governance </b>
                </v-row>
                <v-row>
                  <label>
                    Mengubah tata kelola dari birokrasi tradisional menjadi
                    lebih efisien, efektif, cepat, dan komunikatif seperti SP2D
                    Online, E-PAD</label
                  >
                </v-row>
              </v-col>
              <br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/medal.png" max-width="20px" />
                  <b> Smart Society</b>
                </v-row>
                <v-row>
                  <label>
                    Mendukung kelayakan taraf hidup masyarakat, misalnya melalui
                    peningkatan kualitas pola hidup, kualitas kesehatan, dan
                    transportasi. Dengan ECOSmart, Education (SPC &
                    Edupatrol)</label
                  >
                </v-row>
              </v-col>
              <br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/medal.png" max-width="20px" />
                  <b> Smart Infrastructure</b>
                </v-row>
                <v-row>
                  <label>
                    Sistem teknologi dan Infrastruktur yang memungkinkan
                    terjadinya pemenuhan kebutuhan secara efisien dan cepat.
                    Melalui BNI Cash Management.</label
                  >
                </v-row>
              </v-col>
              <br />
              <b class="orangebni--text" style="font-size:18px"
                ># Dukungan Solusi BNI</b
              >
              <div>
                Kemudian BNI juga mempunyai solusi untuk mendukung konsep yang
                ada, yaitu :
              </div>
              <br /><br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <b> Smart Goverment</b>
                </v-row>
                <v-row>
                  <label
                    >Memberikan Solusi berbasis “e”. Seperti, E-PBB, e-PDAM,
                    e-PTSP, e-Retribusi Pasar, e-Pajak Daerah, e-Samsat, SP2D
                    Online, BNIDirect (eTax dan ePayment), VA Debit, GB Online.
                  </label>
                  <br />
                </v-row>
              </v-col>
              <br /><br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <b> Smart Living</b>
                </v-row>
                <v-row>
                  <label
                    >Dengan Solusi Kartu Multi Fungsi (KMF) atau BNI Smart Card,
                    BNI Smart Hospital</label
                  >
                </v-row>
              </v-col>
              <br /><br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <b>Smart Environtment</b>
                </v-row>
                <v-row>
                  <label>
                    Solusi Layanan melalui Outlet dan e-Channel serta solusi
                    cash management</label
                  >
                </v-row>
              </v-col>
              <br /><br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <b> Smart Economy</b>
                </v-row>
                <v-row>
                  Solusi pembiayaan KUR bagi UMKM, GB Online, Agen46 (Bansos,
                  Bumdes), Smart Card, berbagai jenis simpanan bagi masyarakat
                  dan dukungan e-Channel BN
                </v-row>
              </v-col>
              <br /><br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <b>Smart People</b>
                </v-row>
                <v-row>
                  <label>
                    Melalui solusi e-Smart Community, BNI eduPATROL, Smart
                    Tenant, TapCash, LinkAja</label
                  >
                </v-row>
              </v-col>
              <br /><br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <b> Smart Mobility</b>
                </v-row>
                <v-row>
                  <label>
                    Solusi e-Commerce (BNI Marketplace), Smart Card (KMF,
                    Tourist Card).</label
                  >
                </v-row>
              </v-col>
              <br />

              <b class="orangebni--text" style="font-size:20px"
                >Untuk informasi lebih lanjut dapat menghubungi</b
              >
              <v-container>
                <v-row>
                  <v-col cols="4">
                    <img
                      src="@/assets/img/message.png"
                      style="max-width: 20px;"
                    />
                    <label> Email: </label>
                    <label> tbs_sat@bni.co.id</label>
                  </v-col>
                  <v-col cols="4">
                    <img
                      src="@/assets/img/phone-call.png"
                      style="max-width: 20px;"
                    /><label> telepon: </label>
                    <label> 021 299 460 46</label>
                  </v-col>
                </v-row>
                <v-row>
                  <v-col cols="4">
                    <img
                      src="@/assets/img/whatsapp2.png"
                      style="max-width: 20px;"
                    />
                    <label> WhatsApps: </label>
                    <label> +62 858 5000 1946</label>
                  </v-col>
                  <v-col cols="4">
                    <img
                      src="@/assets/img/telegram.png"
                      style="max-width: 20px;"
                    /><label> Telegram: </label>
                    <label> +62 858 5000 1946</label>
                  </v-col>
                </v-row>
              </v-container>
            </v-card-text>
          </v-col>
        </v-col>
        <!-- <v-btn
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
        </v-btn> -->
      </v-card-text>

      <v-divider></v-divider>
      <v-card-actions class="justify-end">
        <v-btn text @click="dialog = false">Close</v-btn>
      </v-card-actions>
    </v-card>
  </v-dialog>
</template>

<script>
export default {
  data() {
    return {
      dialogm1: "",
      dialog: false,
    };
  },
};
</script>
