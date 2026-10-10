# Android Call Forwarding & Security Recovery

> Panduan untuk memeriksa pengalihan panggilan, menonaktifkan layanan yang tidak dikenal, dan mengamankan Android.

---

## 1. Memeriksa Pengalihan Panggilan

Buka aplikasi Telepon, masukkan kode berikut, lalu tekan tombol panggil jika diperlukan.

| Kode | Fungsi |
|---|---|
| `*#21#` | Memeriksa pengalihan semua panggilan |
| `*#61#` | Memeriksa pengalihan saat tidak dijawab |
| `*#62#` | Memeriksa pengalihan saat tidak terjangkau |
| `*#67#` | Memeriksa pengalihan saat sibuk |

Catat hasilnya. Nomor pesan suara operator tidak otomatis menandakan penyalahgunaan.

---

## 2. Menghapus Pengalihan yang Tidak Diinginkan

Kode berikut dapat digunakan pada jaringan yang mendukungnya.

| Kode | Fungsi |
|---|---|
| `##21#` | Meminta penghapusan pengalihan semua panggilan |
| `##61#` | Meminta penghapusan pengalihan saat tidak dijawab |
| `##62#` | Meminta penghapusan pengalihan saat tidak terjangkau |
| `##67#` | Meminta penghapusan pengalihan saat sibuk |
| `##002#` | Meminta penghapusan seluruh pengalihan |

> Perhatian: `##002#` dapat menghapus pengalihan pesan suara yang sah. Jika ragu, hubungi operator terlebih dahulu.

Setelah menjalankan kode, periksa kembali status pengalihan. Jika gagal, gunakan menu pengaturan panggilan atau minta bantuan operator.

---

## 3. Mematikan Pengalihan Melalui Pengaturan

Nama menu dapat berbeda pada setiap perangkat.

1. Buka aplikasi Telepon.
2. Buka menu Pengaturan.
3. Cari Calling accounts, Supplementary services, atau Call forwarding.
4. Pilih SIM yang ingin diperiksa.
5. Nonaktifkan pengalihan yang tidak dikenal.
6. Ulangi pemeriksaan untuk SIM lainnya jika menggunakan dua SIM.

Jika menu tidak tersedia, minta operator memeriksa pengaturan jaringan.

---

## 4. Mengamankan SMS dan OTP

Kode pengalihan panggilan tidak otomatis menghapus atau menonaktifkan penerusan SMS.

Lakukan langkah berikut:

- Periksa izin SMS dan akses notifikasi setiap aplikasi.
- Periksa izin Accessibility dan administrator perangkat.
- Hapus akses aplikasi yang tidak dikenal setelah memverifikasi fungsinya.
- Periksa perangkat yang terhubung ke akun Google dan layanan pesan.
- Jangan pernah memberikan OTP, PIN SIM, atau kode pemulihan kepada orang lain.
- Hubungi operator jika SIM mendadak kehilangan layanan atau ada permintaan penggantian SIM yang tidak Anda lakukan.

---

## 5. Jika Mencurigai HP Disalahgunakan

1. Amankan akun Google dan email dari perangkat tepercaya.
2. Ganti kata sandi jika ada indikasi akun diambil alih.
3. Aktifkan verifikasi dua langkah.
4. Periksa aplikasi yang terpasang dan hapus aplikasi berbahaya.
5. Perbarui Android dan aplikasi.
6. Hubungi operator untuk memeriksa pengalihan dan keamanan SIM.
7. Jika masalah berlanjut, cadangkan data penting dan pertimbangkan reset pabrik.

> Reset pabrik tidak otomatis memperbaiki masalah akun atau jaringan operator. Amankan akun dan verifikasi layanan jaringan juga.

---

## 6. Cara Mewaspadai Penipuan Kode

- Jangan menjalankan kode yang dikirim orang asing.
- Jangan memasukkan nomor tujuan yang tidak dikenal.
- Jangan percaya klaim bahwa satu kode bisa mendeteksi semua bentuk penyadapan.
- Jangan menginstal aplikasi keamanan dari tautan mencurigakan.
- Verifikasi perubahan melalui operator resmi.

---

## 7. Catatan Keamanan

Hasil kode MMI bergantung pada operator, perangkat, dan firmware. Pengalihan panggilan yang aktif bukan bukti pasti penyadapan; layanan pesan suara dapat menggunakannya secara normal.

Tujuan panduan ini adalah membantu pemilik perangkat memeriksa dan memulihkan pengaturan miliknya sendiri secara aman.

[← Panduan Utama](01-android-secret-codes-call-forwarding-security.md) | [← Panduan Keamanan](README.md) | [🏠 Beranda](../../README.md)
