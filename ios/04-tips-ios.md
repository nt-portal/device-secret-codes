# Tips iOS Tanpa Kode Dial 💡

> Karena di iOS kodenya dikit banget, mending manfaatin menu resmi Apple — lebih aman dan lengkap kok.

## Cek Info Tanpa Kode

| Mau cek... | Bukanya di... |
|---|---|
| IMEI, serial, EID, modem firmware | Settings → General → About |
| SAR & regulasi | Settings → General → Legal & Regulatory |
| Kesehatan baterai & cycle (iOS 17+) | Settings → Battery → Battery Health & Charging |
| Info sinyal & operator, ICCID | Settings → General → About |
| Versi carrier settings | Settings → General → About → tap Carrier |

## Diagnostik Hardware

- **Apple Diagnostics (remote):** Hubungin Apple Support, nanti mereka kirimin link diagnostik ke iPhone kamu.
- **Cek log crash:** Settings → Privacy & Security → Analytics → cari log `panic-*`.
- **Sinyal:** Pakai Field Test `*3001#12345#*` → [02-field-test-mode.md](02-field-test-mode.md)

## Kalau Kode MMI Invalid

1. Update iOS dulu (Settings → General → Software Update).
2. Aktifin Airplane Mode 5 detik, matiin lagi.
3. Coba SIM lain atau eSIM.
4. Reset Network Settings: Settings → General → Transfer or Reset → Reset → Reset Network Settings (Wi-Fi password bakal kehapus).

[← Kode Lainnya](03-kode-iphone-lainnya.md) | [Ke Umum →](../umum/README.md) | [🏠 Beranda](../README.md)
