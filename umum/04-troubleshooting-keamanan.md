# Troubleshooting & Keamanan — Semua HP 🔧🔒

## Jika Kode Tidak Berfungsi

| Gejala | Penyebab | Solusi |
|---|---|---|
| Mengetik kode terakhir tidak ada respons | Bukan dialer bawaan / diblokir vendor (Android 12+ / iOS) | Gunakan **Phone bawaan**; di Android coba *Activity Launcher / Force LTE Only* |
| `Connection problem / MMI invalid` | Sinyal lemah / salah ketik `*`/`#` | Aktifkan Airplane mode 5 detik → coba lagi; periksa penulisan |
| `*#*#4636#*#*` tidak terbuka | Diblokir Google/vendor | Gunakan aplikasi shortcut — lihat [android/01-cara-menggunakan.md](../android/01-cara-menggunakan.md) |
| Field Test tidak terbuka (iPhone/HarmonyOS) | Versi iOS/EMUI terlalu lama | Perbarui sistem operasinya terlebih dahulu |
| `*#0*#` tidak berfungsi (Samsung) | Region/Go firmware | Gunakan Samsung Members → Diagnostics |

## Keamanan & Privasi — Sangat Penting!

- **Jangan menyebarkan IMEI** (`*#06#`) di media sosial — rawan dikloning.
- **Jangan mengetik kode dari orang asing** — `**21*08xxxx#` berarti mengaktifkan pengalihan ke penipu! Verifikasi terlebih dahulu dengan `*#21#`.
- Pengalihan ke **voicemail operator** adalah hal yang normal, bukan tanda penyadapan.
- Lakukan backup terlebih dahulu sebelum mencoba reset — baik `*#*#7780#*#*` (Android), `*#7370#` (Nokia), maupun Reset Network Settings (iOS).

[← Tips Mengingat](03-tips-mengingat-kode.md) | [Lanjut ke Referensi →](05-referensi.md)
