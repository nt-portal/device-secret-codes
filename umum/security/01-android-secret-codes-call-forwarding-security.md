# Android Secret Codes & Call Forwarding Security

> Panduan edukasi mengenai kode dial Android, kode MMI/USSD, pengalihan panggilan, layanan operator, diagnostik perangkat, risiko penyalahgunaan, dan cara melindungi privasi.

Tujuan panduan ini adalah membantu Anda memahami kode telepon dan mengenali perubahan layanan yang tidak Anda kenali.

> [!WARNING]
> Kode bergantung pada operator, negara, perangkat, dan firmware. Jangan menjalankan kode yang belum dipahami. Kode pengalihan dapat mengubah tujuan panggilan, sedangkan kode tertentu pada perangkat lama dapat menghapus data.

---

## Daftar Isi

- [1. Istilah Dasar](#1-istilah-dasar)
- [2. Cara Menjalankan Kode](#2-cara-menjalankan-kode)
- [3. Kode Informasi Perangkat](#3-kode-informasi-perangkat)
- [4. Pengalihan Panggilan](#4-pengalihan-panggilan)
- [5. Format Kode dengan Nomor Tujuan](#5-format-kode-dengan-nomor-tujuan)
- [6. Memeriksa dan Menghapus Pengalihan](#6-memeriksa-dan-menghapus-pengalihan)
- [7. Pengalihan SMS dan Pesan](#7-pengalihan-sms-dan-pesan)
- [8. Panggilan Tunggu dan Identitas Pemanggil](#8-panggilan-tunggu-dan-identitas-pemanggil)
- [9. Kode Diagnostik Android](#9-kode-diagnostik-android)
- [10. Kode Berdasarkan Merek](#10-kode-berdasarkan-merek)
- [11. Risiko dan Penyalahgunaan](#11-risiko-dan-penyalahgunaan)
- [12. Cara Mengatasi Pengalihan Tidak Dikenal](#12-cara-mengatasi-pengalihan-tidak-dikenal)
- [13. FAQ](#13-faq)
- [14. Disclaimer](#14-disclaimer)

---

## 1. Istilah Dasar

| Istilah | Arti |
|---|---|
| USSD | Kode layanan yang berkomunikasi dengan jaringan operator |
| MMI | Kode perintah layanan pada antarmuka telepon seluler |
| Call forwarding | Pengalihan panggilan ke tujuan lain |
| Conditional forwarding | Pengalihan hanya pada kondisi tertentu |
| Unconditional forwarding | Pengalihan semua panggilan sesuai layanan operator |
| IMEI | Identitas perangkat seluler |
| VoLTE | Panggilan suara melalui jaringan LTE |
| VoWiFi | Panggilan suara melalui Wi-Fi |
| SMS forwarding | Penerusan pesan SMS melalui mekanisme operator atau aplikasi; bukan fitur universal kode MMI |

> Kode yang terlihat mirip belum tentu memiliki fungsi yang sama. Dukungan kode ditentukan oleh jaringan dan perangkat.

---

## 2. Cara Menjalankan Kode

1. Buka aplikasi Telepon bawaan.
2. Pilih keypad atau papan tombol.
3. Ketik kode lengkap, termasuk tanda `*` dan `#`.
4. Untuk kode diagnostik, tunggu apakah menu muncul otomatis.
5. Untuk kode layanan operator, tekan tombol panggil jika diperlukan.
6. Baca pesan hasilnya sebelum melakukan tindakan lanjutan.

Jika kode tidak bekerja, jangan mengulanginya secara membabi buta. Periksa dokumentasi operator dan model perangkat.

---

## 3. Kode Informasi Perangkat

| Kode | Fungsi |
|---|---|
| `*#06#` | Melihat IMEI |
| `*#07#` | Informasi SAR/regulasi jika didukung |
| `*#*#4636#*#*` | Informasi telepon dan jaringan pada perangkat tertentu |
| `*#*#225#*#*` | Informasi kalender pada perangkat tertentu |
| `*#*#426#*#*` | Diagnostik Firebase Cloud Messaging pada perangkat tertentu |
| `*#*#44336#*#*` | Informasi versi/build pada perangkat tertentu |

> Kode ini tidak membuktikan apakah HP disadap.

---

## 4. Pengalihan Panggilan

Pengalihan panggilan memungkinkan panggilan masuk dialihkan ke nomor lain sesuai kondisi dan dukungan operator.

| Kode pemeriksaan | Kondisi |
|---|---|
| `*#21#` | Pengalihan semua panggilan |
| `*#61#` | Pengalihan ketika tidak dijawab |
| `*#62#` | Pengalihan ketika tidak terjangkau |
| `*#67#` | Pengalihan ketika sibuk |
| `*#004#` | Pengalihan bersyarat, jika didukung |

> Hasil pemeriksaan dapat menunjukkan nomor layanan pesan suara milik operator. Hal ini tidak otomatis berarti terjadi penyadapan.

---

## 5. Format Kode dengan Nomor Tujuan

Kode berikut adalah format standar MMI yang lazim digunakan pada jaringan GSM. Dukungan dan sintaks persisnya dapat berbeda.

| Format | Fungsi |
|---|---|
| `**21*nomor#` | Meminta aktivasi pengalihan semua panggilan |
| `**61*nomor#` | Meminta aktivasi pengalihan saat tidak dijawab |
| `**62*nomor#` | Meminta aktivasi pengalihan saat tidak terjangkau |
| `**67*nomor#` | Meminta aktivasi pengalihan saat sibuk |

`nomor` adalah placeholder, bukan teks yang harus diketik secara harfiah.

Contoh penulisan format: `**21*+62XXXXXXXXXX#`

Huruf `X` hanya penanda contoh. Jangan menjalankan contoh tersebut apa adanya.

Sebelum mengaktifkan pengalihan:

- Pastikan nomor tujuan adalah nomor milik sendiri atau nomor yang memang berwenang menerima panggilan.
- Pastikan operator mendukung layanan tersebut.
- Pahami bahwa panggilan masuk dapat dialihkan dari nomor asal.
- Jangan memasukkan nomor asing yang dikirim melalui pesan atau situs tidak dikenal.

---

## 6. Memeriksa dan Menghapus Pengalihan

| Kode | Fungsi |
|---|---|
| `*#21#` | Memeriksa pengalihan semua panggilan |
| `*#61#` | Memeriksa pengalihan saat tidak dijawab |
| `*#62#` | Memeriksa pengalihan saat tidak terjangkau |
| `*#67#` | Memeriksa pengalihan saat sibuk |
| `##21#` | Meminta penghapusan pengalihan semua panggilan |
| `##61#` | Meminta penghapusan pengalihan saat tidak dijawab |
| `##62#` | Meminta penghapusan pengalihan saat tidak terjangkau |
| `##67#` | Meminta penghapusan pengalihan saat sibuk |
| `##002#` | Meminta penghapusan seluruh pengalihan yang didukung jaringan |

> Perhatian: `##002#` dapat menghapus pengalihan ke pesan suara yang sebenarnya masih dibutuhkan. Gunakan hanya jika memahami dampaknya. Konfirmasikan perubahan melalui pesan balasan jaringan atau operator.

---

## 7. Pengalihan SMS dan Pesan

Tidak ada satu kode MMI universal yang dapat mengalihkan semua SMS pada semua operator.

Penerusan pesan dapat terjadi melalui mekanisme berbeda:

- Fitur penerusan pesan di aplikasi.
- Sinkronisasi pesan dengan perangkat lain.
- Aplikasi pihak ketiga yang memiliki akses SMS.
- Akses akun atau perangkat yang tidak sah.
- Layanan khusus dari operator, jika tersedia.

**Cara memeriksa risiko SMS:**

1. Periksa aplikasi yang memiliki izin SMS.
2. Periksa izin aksesibilitas dan akses notifikasi.
3. Periksa perangkat yang terhubung ke akun Google atau layanan pesan.
4. Hapus izin aplikasi yang tidak dikenal setelah memastikan fungsinya.
5. Hubungi operator jika SMS atau OTP tidak diterima, SIM tiba-tiba kehilangan layanan, atau ada perubahan akun yang tidak Anda lakukan.

> Jangan mengetik kode pengalihan panggilan dengan anggapan bahwa kode tersebut akan meneruskan SMS. Pengalihan panggilan dan penerusan SMS merupakan hal berbeda.

---

## 8. Panggilan Tunggu dan Identitas Pemanggil

Kode yang umum tersedia pada sejumlah jaringan:

| Kode | Fungsi |
|---|---|
| `*#43#` | Memeriksa status panggilan tunggu |
| `*43#` | Meminta aktivasi panggilan tunggu |
| `#43#` | Meminta penonaktifan panggilan tunggu |
| `*#30#` | Memeriksa status identitas pemanggil pada jaringan yang mendukung |
| `*#31#` | Memeriksa status pembatasan identitas pemanggil pada perangkat/jaringan tertentu |
| `#31#nomor` | Meminta penyembunyian nomor untuk panggilan tertentu pada layanan yang mendukung |

> Hasilnya tergantung operator. Jangan menganggap semua kode berfungsi pada setiap SIM.

---

## 9. Kode Diagnostik Android

| Kode | Fungsi |
|---|---|
| `*#*#2664#*#*` | Tes layar sentuh pada perangkat tertentu |
| `*#*#2663#*#*` | Informasi firmware layar sentuh |
| `*#*#0842#*#*` | Tes getaran/lampu layar pada perangkat tertentu |
| `*#*#0283#*#*` | Tes audio loopback pada perangkat tertentu |
| `*#*#0588#*#*` | Tes sensor kedekatan pada perangkat tertentu |
| `*#*#232331#*#*` | Tes Bluetooth pada perangkat tertentu |
| `*#*#232339#*#*` | Tes Wi-Fi pada perangkat tertentu |

> Tidak semua kode diagnostik masih tersedia pada Android modern.

---

## 10. Kode Berdasarkan Merek

### Samsung

| Kode | Fungsi |
|---|---|
| `*#0*#` | Tes hardware pada model tertentu |
| `*#0011#` | Informasi jaringan |
| `*#0228#` | Informasi baterai |
| `*#1234#` | Versi firmware |
| `*#9900#` | Menu diagnostik SysDump pada model tertentu |
| `*#2263#` | Pemilihan band pada model tertentu |

### Xiaomi, Redmi, dan POCO

| Kode | Fungsi |
|---|---|
| `*#*#6484#*#*` | Menu tes hardware CIT pada model tertentu |
| `*#*#64663#*#*` | Menu tes hardware pada model tertentu |
| `*#*#6485#*#*` | Informasi baterai pada model tertentu |
| `*#*#86583#*#*` | Mengubah pemeriksaan operator VoLTE pada model tertentu |
| `*#*#869434#*#*` | Mengubah pemeriksaan operator VoWiFi pada model tertentu |

### Merek Lainnya

| Merek | Kode | Fungsi |
|---|---|---|
| Huawei | `*#*#2846579#*#*` | Menu Project pada model tertentu |
| Vivo | `*#558#` | Tes hardware pada model tertentu |
| OPPO/Realme | `*#899#` | Menu engineering pada model tertentu |
| Sony Xperia | `*#*#7378423#*#*` | Menu layanan pada model tertentu |

> Kode merek bukan standar universal. Verifikasi kompatibilitas sebelum mencantumkannya sebagai teruji.

---

## 11. Risiko dan Penyalahgunaan

**Risiko pengalihan panggilan**

Pengalihan yang tidak dikenal dapat menyebabkan panggilan masuk dialihkan ke nomor lain. Dampaknya bergantung pada jenis pengalihan dan layanan operator.

**Risiko aplikasi berbahaya**

Aplikasi dengan izin SMS, notifikasi, aksesibilitas, atau administrator perangkat dapat menyalahgunakan aksesnya.

**Risiko kode reset**

Kode tertentu pada perangkat lama dapat memicu reset atau penghapusan data. Hindari kode reset tersembunyi yang tidak terdokumentasi.

**Risiko engineering mode**

Pengaturan modem, band jaringan, dan konfigurasi teknis yang salah dapat mengganggu koneksi atau fungsi perangkat.

---

## 12. Cara Mengatasi Pengalihan Tidak Dikenal

1. Catat hasil pemeriksaan dan waktu kejadian.
2. Jangan langsung menyimpulkan bahwa perangkat disadap.
3. Buka pengaturan panggilan dan periksa menu pengalihan.
4. Hubungi operator melalui kanal resmi untuk memverifikasi pengaturan jaringan.
5. Jika pengalihan tidak diinginkan, minta operator menghapusnya atau gunakan kode penonaktifan yang sesuai.
6. Periksa keamanan akun Google dan aplikasi yang memiliki akses sensitif.
7. Jika ada dugaan pengambilalihan SIM, segera hubungi operator dan amankan akun penting.

> Jika menggunakan `##002#`, verifikasi kembali pengalihan setelahnya karena pesan suara mungkin ikut terpengaruh.

---

## 13. FAQ

**Apakah `*#21#` dapat mendeteksi penyadapan?**

Tidak. Kode ini memeriksa status pengalihan panggilan yang dilaporkan jaringan, bukan mendeteksi seluruh bentuk penyadapan.

**Apakah pengalihan ke nomor operator berbahaya?**

Tidak selalu. Nomor tersebut dapat digunakan untuk layanan pesan suara atau pengalihan bersyarat yang normal.

**Apakah ada kode universal untuk meneruskan SMS?**

Tidak ada kode universal yang menjamin penerusan SMS di semua Android dan operator.

**Mengapa kode tidak berfungsi?**

Penyebabnya dapat berupa firmware, aplikasi Telepon, operator, jaringan, atau kode yang sudah tidak didukung.

**Apakah kode diagnostik dapat membuka semua fitur tersembunyi?**

Tidak. Menu yang tersedia ditentukan oleh produsen dan firmware perangkat.

---

## 14. Disclaimer

Repositori ini dibuat untuk edukasi, diagnostik perangkat, dan perlindungan pengguna. Penulis tidak menjamin setiap kode kompatibel dengan seluruh perangkat atau jaringan.

Jangan menggunakan kode untuk mengubah layanan milik orang lain tanpa izin. Pengguna bertanggung jawab memastikan bahwa tindakan yang dilakukan sesuai dengan ketentuan operator dan hukum yang berlaku.

**Kontribusi**

Kirim pull request dengan menyertakan:

- Merek dan model perangkat.
- Versi Android dan firmware.
- Operator dan negara, jika relevan.
- Kode yang diuji.
- Hasil pengujian dan risiko yang teramati.

Kode yang belum diverifikasi harus diberi label Unverified.

**Lisensi**

MIT License — lihat berkas `LICENSE`.

[← Panduan Keamanan](README.md) | [Lanjut ke Pemulihan →](02-android-call-forwarding-security-recovery.md) | [🏠 Beranda](../../README.md)
