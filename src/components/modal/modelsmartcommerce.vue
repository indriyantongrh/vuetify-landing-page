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
      <v-toolbar color="hijaubni" dark>BNI Smartcommerce </v-toolbar>

      <v-card-text>
        <v-col cols="12" class="d-flex align-center">
          <v-col>
            <v-card-text>
              <!-- <v-img src="@/assets/img/ecommerce.jpg" max-width="250px" /> -->
              <b class="orangebni--text" style="font-size:20px"
                >Apa itu BNI Smart Commerce?</b
              >
              <div>
                <b>BNI Smart Commerce </b> adalah solusi digital khusus untuk
                suatu komunitas/ekosistem bisnis yang terdiri dari Penjual dan
                Pembeli, yang dikembangkan diatas platform BNIDirect, untuk
                menatalaksanakan transaksi pembayaran jual-beli secara efektif
                dan efisien.
              </div>
              <br />
              <b class="orangebni--text" style="font-size:20px"
                >Ruang Lingkup</b
              >
              <div>
                BNI Smart Commerce ditujukan untuk membantu para nasabah
                Business Banking yang tergabung dalam ekosistem/komunitas bisnis
                dalam menatalaksanakan transaksi pembayaran jual-beli, meliputi
                fungsi-fungsi :
                <b>
                  Commerce Ecosystem Management, Commercial Doc. Presentation,
                  Transhipment Doc. Presentation, Certificate of Inspection,
                  Buyer’s Acceptance, Payment Instruction, dan Special Product
                  Offering.
                </b>
              </div>

              <br /><br />
              <b class="orangebni--text" style="font-size:20px"
                >Manfaat BNI Smart Commerce</b
              >
              <br /><br />
              <v-row>
                <v-img src="@/assets/img/checklist.png" max-width="20px" />
                <label>
                  Simplifikasi alur proses dalam mekanisme transaksional
                  perbankan pada ekosistem bisnis</label
                >
              </v-row>
              <v-row>
                <v-img src="@/assets/img/checklist.png" max-width="20px" />
                <label>
                  Kemudahan pemantauan (monitoring) penyelesaian pembayaran
                  transaksi jual-beli perusahaan</label
                >
              </v-row>
              <v-row>
                <v-img src="@/assets/img/checklist.png" max-width="20px" />
                <label>
                  Peningkatan efektifitas dan efisiensi transaksional
                  perbankan</label
                >
              </v-row>
              <v-row>
                <v-img src="@/assets/img/checklist.png" max-width="20px" />
                <label>
                  Jaminan kecepatan & keamanan tatakelola transaksional
                  perbankan perusahaan</label
                >
              </v-row>
              <v-row>
                <v-img src="@/assets/img/checklist.png" max-width="20px" />
                <label>
                  Meningkatkan kualitas Account Payable dan Account Receivable
                  perusahaan</label
                >
              </v-row>
              <v-row>
                <v-img src="@/assets/img/checklist.png" max-width="20px" />
                <label>
                  Meningkatkan kepercayaan diantara entitas dalam ekosistem
                  bisni</label
                >
              </v-row>
              <br /><br />
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
