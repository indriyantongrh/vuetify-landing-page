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
      <v-toolbar color="hijaubni" dark>BNI ECOSmart </v-toolbar>

      <v-card-text>
        <v-col cols="12" class="d-flex align-center">
          <v-col>
            <v-card-text>
              <!-- <v-img src="@/assets/img/ecommerce.jpg" max-width="250px" /> -->

              <div>
                <b>BNI ECOSmart </b> merupakan solusi yang khusus dirancang
                untuk membantu nasabah perusahaan dalam melakukan aktivitas
                pengelolaan member untuk berbagai ecosystem secara optimal,
                efektif, efisien yang dilengkapi dengan berbagai fitur unggulan.
              </div>
              <br />

              <div>
                <b>BNI ECOSmart</b> juga dapat menjadi solusi bagi perusahaan
                dalam melakukan pengelolaan dan pembuatan tagihan, pelaporan dan
                dashboard pembayaran, monitoring pembayaran serta penyampaian
                informasi dan berita.
              </div>
              <br />
              <div>
                Dengan <b> BNI ECOSmart </b> implementasi akan lebih mudah dan
                cepat dengan adanya pilihan skema integrasi yang telah
                disesuaikan dengan kebutuhan bisnis Anda.
              </div>

              <br />
              <div>
                <b>BNI ECOSmart </b> telah didukung dengan layanan BNI
                e-Collection (BNI Virtual Account) yang dirancang untuk membantu
                management perusahaan dalam mengelola aktivitas penerimaan dana
                (collection) secara optimal, serta untuk identifikasi pembayar.
                Selain itu didukung juga dengan layanan BNIDirect untuk
                kemudahan pembayaran operasional tenant dan tersedia pula
                Dashboard untuk kemudahan pelaporan.
              </div>
              <br />
              <b class="orangebni--text" style="font-size:18px"># Fitur</b>
              <br /><br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <b> Mobile Friendly</b>
                </v-row>
                <v-row>
                  <label
                    >Seluruh tagihan dengan mudah diakses melalui mobile
                    Aplikasi BNI ECOSmart baik melalui Aplikasi IOS dan Android
                  </label>
                  <br />
                </v-row>
              </v-col>
              <br /><br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <b> Informasi Tagihan</b>
                </v-row>
                <v-row>
                  <label
                    >Tidak perlu khawatir dengan melewatkan tanggal jatuh tempo
                    tagihan, BNI ECOSmart memiliki fitur informasi tagihan
                    lengkap dari mulai unpaid, on process hingga history
                    tagihan</label
                  >
                </v-row>
              </v-col>
              <br /><br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <b>User Guide</b>
                </v-row>
                <v-row>
                  <label>
                    Aplikasi mobile BNI ECOSmart sangat mudah digunakan karena
                    dilengkapi dengan user guide yang akan menambah experience
                    dalam menggunakannya</label
                  >
                </v-row>
              </v-col>
              <br /><br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <b>Real time notification</b>
                </v-row>
                <v-row>
                  Konfirmasi pembayaran secara otomatis dan realtime
                </v-row>
              </v-col>
              <br /><br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <b>Handling Complaint</b>
                </v-row>
                <v-row>
                  <label>
                    Nasabah dapat menggunakan fitur help untuk mengajukan
                    keluhan/complaint serta melakukan tracking atas proses
                    complaint tersebut</label
                  >
                </v-row>
              </v-col>
              <br /><br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/checklist.png" max-width="20px" />
                  <b>Chat with the Owner</b>
                </v-row>
                <v-row>
                  <label>
                    Nasabah dapat menggunakan fitur chat di aplikas BNI ECOSmart
                    Mobile untuk bertanya dan memberikan saran kepada
                    Management</label
                  >
                </v-row>
              </v-col>
              <br />
              <b class="orangebni--text" style="font-size:18px"># Keunggulan</b>
              <br /><br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/medal.png" max-width="20px" />
                  <b>Cepat dan Mudah</b>
                </v-row>
                <v-row>
                  <label>
                    Implementasi mudah dan cepat dengan beberapa pilihan skema
                    integrasi yang disesuaikan dengan kebutuhan bisnis
                    Anda</label
                  >
                </v-row>
              </v-col>
              <br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/medal.png" max-width="20px" />
                  <b>Fleksibilitas Implementasi</b>
                </v-row>
                <v-row>
                  <label>
                    Dapat di implementasikan di berbagai ekosistem seperti :
                    Apartment, Kondotel, Pasar, Keanggotaan, Kawasan Industri,
                    dll</label
                  >
                </v-row>
              </v-col>
              <br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/medal.png" max-width="20px" />
                  <b> Komunikasi Dua Arah</b>
                </v-row>
                <v-row>
                  <label>
                    kemudahan dalam melakukan komunikasi dua arah antara
                    Manajemen dan client</label
                  >
                </v-row>
              </v-col>
              <br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/medal.png" max-width="20px" />
                  <b> Fleksibilitas Cara Pembayaran</b>
                </v-row>
                <v-row>
                  <label>
                    Kemudahan pembayaran tagihan oleh customer Anda di seluruh
                    chanel Bank di Indonesia</label
                  >
                </v-row>
              </v-col>
              <br />
              <v-col>
                <v-row>
                  <v-img src="@/assets/img/medal.png" max-width="20px" />
                  <b> Dashboard, Report & Rekonsiliasi Realtime & Online</b>
                </v-row>
                <v-row>
                  <label>
                    Tersedia Dashboard bagi manajemen dan sistem reporting dan
                    rekonsiliasi yang dapat disesuaikan dengan kebutuhan
                    manajemen dan dapat diakses secara real time online (akurat,
                    cepat, dan tepat)</label
                  >
                </v-row>
              </v-col>
              <v-col align="center">
                <v-img src="@/assets/img/ecosmart3.png" max-width="450px" />
                <br />
                <v-img src="@/assets/img/ecosmart4.png" max-width="550px" />
              </v-col>

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
