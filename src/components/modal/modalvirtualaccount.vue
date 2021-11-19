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
      <v-toolbar color="hijaubni" dark> BNI Bank Guarantee </v-toolbar>

      <v-card-text>
        <v-col cols="12" class="d-flex align-center">
          <v-col>
            <v-card-text>
              <!-- <v-img src="@/assets/img/ecommerce.jpg" max-width="250px" /> -->
              <b class="orangebni--text" style="font-size:20px">Garansi Bank</b>
              <div>
                BNI sebagai partner usaha memahami kebutuhan Anda dalam
                memperlancar transaksi perdagangan atau proyek yang umumnya
                mempersyaratkan penyertaan Jaminan Bank (Garansi Bank). Kami
                memahami tujuan dan kebutuhan Nasabah berbeda-beda, karena itu
                kami telah mendesain produk Garansi Bank ini sesuai dengan
                tujuan dan kebutuhan Anda. <b>BNI Garansi Bank</b> merupakan
                pernyataan secara tertulis dari BNI yang berisi kesanggupan
                untuk menjamin pembayaran sejumlah uang kepada penerima jaminan
                (bowheer), apabila pihak yang dijamin (applicant) wanprestasi
                atau tidak dapat memenuhi kewajiban yang telah diperjanjikan
                dalam suatu perjanjian kerjasama/ kontrak.
              </div>
              <br />
              <b class="orangebni--text" style="font-size:20px"
                >Jenis BNI Garansi Bank</b
              >
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <label> Jaminan Penawaran (Bid Bond)</label>
                </v-row>
              </v-col>
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <label> Jaminan Pelaksanaan (Performance Bond)</label>
                </v-row>
              </v-col>
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <label> Jaminan Uang Muka (Advance Payment Bond)</label>
                </v-row>
              </v-col>
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <label> Jaminan Sanggahan Banding</label>
                </v-row>
              </v-col>
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <label>
                    Jaminan Lainnya (Jaminan Pembayaran, Jaminan Reklamasi,
                    Jaminan dalam rangka Kepabeanan/Bea Cukai, dsb)</label
                  >
                </v-row>
              </v-col>
              <br />
              <b class="orangebni--text" style="font-size:20px"
                >Manfaat BNI Garansi Bank</b
              >
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <label>
                    Menjamin perusahaan dalam melakukan kegiatan bisnis</label
                  >
                </v-row>
              </v-col>
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <label>
                    Dapat dipergunakan untuk transaksi domestik maupun
                    internasional</label
                  >
                </v-row>
              </v-col>
              <br />
              <b class="orangebni--text" style="font-size:20px"
                >Keunggulan BNI Garansi Bank</b
              >
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <label> Selesai pada hari yang sama</label>
                </v-row>
              </v-col>
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <label> Aman dan terpercaya</label>
                </v-row>
              </v-col>
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <label> Proses mudah</label>
                </v-row>
              </v-col>
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <label> Format dapat disesuaikan</label>
                </v-row>
              </v-col>
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <label> Biaya kompetitif</label>
                </v-row>
              </v-col>
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <label> Fleksibilitas jaminan</label>
                </v-row>
              </v-col>

              <div>
                Seiring dengan perkembangan teknologi, BNI menghadirkan Garansi
                Bank Online (BNI e-Bank Guarantee dan m-BG Checking) sebagai
                solusi yang memberikan kemudahan bagi nasabah dalam melakukan
                permohonan penerbitan, pemantauan dan pengecekan garansi bank
                secara online
              </div>
              <br />
              <b class="orangebni--text" style="font-size:20px"
                >Manfaat bagi Nasabah</b
              >
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <label> Mudah</label>
                </v-row>
              </v-col>
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <label> Hemat waktu dan biaya</label>
                </v-row>
              </v-col>
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <label> Aman</label>
                </v-row>
              </v-col>
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <label> Paperless</label>
                </v-row>
              </v-col>
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <label>
                    Pengajuan dan pemantauan status penerbitan garansi bank
                    secara online</label
                  >
                </v-row>
              </v-col>
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <label> Pengecekan warkat garansi bank secara online</label>
                </v-row>
              </v-col>
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <label>
                    Reporting penerbitan garansi bank dan monitoring plafond
                    garansi bank secara online</label
                  >
                </v-row>
              </v-col>

              <br /><br />
              <b class="orangebni--text" style="font-size:18px"
                >E-Bank Guarantee</b
              >
              <div>
                <b> E-Bank Guarantee</b> adalah solusi web based dari Garansi
                Bank yang memiliki fitur sbb:
              </div>
              <br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/medal.png" max-width="20px" />
                  <b> e-Application</b>
                </v-row>
                <v-row>
                  <label
                    >Pengajuan permohonan penerbitan garansi bank secara online
                    yang dilengkapi dengan approval berjenjang.
                  </label>
                  <br />
                </v-row>
              </v-col>
              <br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/medal.png" max-width="20px" />
                  <b> e-Tracking</b>
                </v-row>
                <v-row>
                  <label>Monitoring status penerbitan garansi bank.</label>
                </v-row>
              </v-col>
              <br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/medal.png" max-width="20px" />
                  <b>e-Reporting</b>
                </v-row>
                <v-row>
                  <label>
                    Report garansi bank yang telah diterbitkan (sebagai
                    applicant) dan diterima (sebagai beneficiary).</label
                  >
                </v-row>
              </v-col>
              <br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/medal.png" max-width="20px" />
                  <b>e-Checking</b>
                </v-row>
                <v-row>
                  Pengecekan keabsahan warkat garansi bank yang telah
                  diterbitkan (sebagai applicant) dan/atau diterima sebagai
                  bowheer.
                </v-row>
              </v-col>
              <br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/medal.png" max-width="20px" />
                  <b> e-Plafond Monitoring</b>
                </v-row>
                <v-row>
                  <label>
                    Pemantauan plafond garansi bank (maksimum, pemakaian dan
                    sisa plafond).</label
                  >
                </v-row>
              </v-col>
              <br /><br />

              <b class="orangebni--text" style="font-size:18px"
                >BNI m-BG Checking</b
              >
              <div>
                Adalah pengecekan kebenaran warkat garansi bank via mobile apps
                melalui scanning QR Code pada garansi bank.
              </div>
              <br />
              <b
                >Cara mendapatkan layanan BNI e-Bank Guarantee & m-BG Checking
              </b>
              <br />
              <v-col cols="12">
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <label>
                    Nasabah mengajukan pendaftaran sebagai user pengguna
                    aplikasi BNI e-Bank Guarantee ke kantor cabang Bni</label
                  >
                  <label>
                    terdekat atau ke Divisi Wholesale Solution (WHS)</label
                  >
                </v-row>
              </v-col>
              <v-col cols="12">
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <label>
                    Nasabah mendaftarkan nama user (maker, approver dan
                    releaser) pada aplikasi BNI e-Bank Guarantee</label
                  >
                </v-row>
              </v-col>
              <v-col cols="12">
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <label>
                    Setelah proses pendaftaran selesai, nasabah akan mendapatkan
                    username dan password untuk mengakses dan</label
                  >
                  <label>
                    menggunakan aplikasi BNI e-bank Guarantee dan diberikan
                    pelatihan penggunaannya.</label
                  >
                </v-row>
              </v-col>
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
