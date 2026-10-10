# iOS — Tips Tanpa Kode Dial

> Karena iOS minim kode rahasia, pakai menu resmi Apple — lebih aman & lengkap.

## Cek Info Perangkat Tanpa Kode

| Mau cek... | Buka... |
|---|---|
| IMEI, serial, EID, modem FW | **Settings → General → About** |
| SAR & regulasi | **Settings → General → Legal & Regulatory** |
| Baterai health & cycle (iOS 17+) | **Settings → Battery → Battery Health & Charging** (cycle count di About) |
| Sinyal & operator, ICCID | **Settings → General → About** (SIM info) |
| Carrier settings version | **Settings → General → About** (tap Carrier) |

## Diagnostik Hardware

- **Apple Diagnostics (remote):** Hubungi Apple Support → mereka kirim link diagnostik ke iPhone.
- **Test manual:** Settings → Privacy & Security → Analytics → cek log `panic-*` untuk crash hardware.
- **Field Test** untuk sinyal: `*3001#12345#*` → [02-field-test-mode.md](02-field-test-mode.md)

## Jika Kode MMI Invalid di iPhone

1. Update ke iOS terbaru (**Settings → General → Software Update**).
2. Toggle Airplane Mode 5 detik.
3. Coba kartu SIM lain / eSIM.
4. Reset Network Settings: **Settings → General → Transfer or Reset → Reset → Reset Network Settings** (hapus Wi-Fi password).

[← 03 Kode Lainnya](03-kode-iphone-lainnya.md) | [→ Umum](../umum/README.md) | [🏠 Beranda](../README.md)
