# Tips iOS Tanpa Kode Dial 💡

> Karena kode di iOS sangat terbatas, sebaiknya manfaatkan menu resmi Apple — lebih aman dan informasinya lebih lengkap.

## Memeriksa Informasi Tanpa Kode

| Ingin memeriksa... | Buka di... |
|---|---|
| IMEI, serial, EID, modem firmware | Settings → General → About |
| SAR dan regulasi | Settings → General → Legal & Regulatory |
| Kesehatan baterai & cycle (iOS 17+) | Settings → Battery → Battery Health & Charging |
| Informasi sinyal & operator, ICCID | Settings → General → About |
| Versi carrier settings | Settings → General → About → ketuk Carrier |

## Diagnostik Hardware

- **Apple Diagnostics (remote):** Hubungi Apple Support, mereka akan mengirimkan tautan diagnostik ke iPhone Anda.
- **Memeriksa log crash:** Settings → Privacy & Security → Analytics → cari log `panic-*`.
- **Pemeriksaan sinyal:** Gunakan Field Test `*3001#12345#*` → [02-field-test-mode.md](02-field-test-mode.md)

## Jika Kode MMI Tidak Valid

1. Perbarui iOS terlebih dahulu (Settings → General → Software Update).
2. Aktifkan Airplane Mode selama 5 detik, lalu nonaktifkan kembali.
3. Coba kartu SIM lain atau eSIM.
4. Reset Network Settings: Settings → General → Transfer or Reset → Reset → Reset Network Settings (password Wi-Fi akan terhapus).

[← Kode Lainnya](03-kode-iphone-lainnya.md) | [Ke Umum →](../umum/README.md) | [🏠 Beranda](../README.md)
