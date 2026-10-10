# HarmonyOS / Huawei EMUI — Kode Lengkap + Contoh

> Jalan di Huawei P/Mate/Nova + Honor lama (EMUI) & HarmonyOS NEXT. Butuh **Phone bawaan Huawei**.

## Cara Pakai

Phone → Keypad → ketik → auto / tap Panggil. Jika tidak jalan → HarmonyOS 3+ kadang disable kode third-party dialer.

## Kode Huawei / HarmonyOS

| Kode | Fungsi | Contoh / Manfaat |
|---|---|---|
| `*#*#2846579#*#*` | **ProjectMenu** (menu utama Huawei) | **Paling penting.** Buka → *Background Settings → Battery / Network Information Query / Veneer Info / Software Upgrade*. Cek battery health tanpa bongkar. |
| `*#*#1357946#*#*` | SN & Product ID | Untuk unlock bootloader/service. **Contoh:** catat SN untuk klaim garansi Huawei. |
| `*#06#` | IMEI | Universal — cek Kemenperin. |
| `*#07#` | SAR / regulasi | |
| `*#*#6130#*#*` | Testing (varian) | Network info (beberapa EMUI). |
| `*#*#2846579159#*#*` | ProjectMenu extended (varian) | |
| `*#*#0000#*#*` | About / version (varian) | Versi HarmonyOS & patch. |

## Universal (juga jalan di HarmonyOS)

` *#21#` `##002#` `*#43#` `*#31#` `*3001#12345#*` (Field Test tidak ada di Huawei — pakai ProjectMenu → Network Info).

→ Detail universal: [umum/01-kode-ussd-mmi-universal.md](../umum/01-kode-ussd-mmi-universal.md)

## Tips HarmonyOS

- HarmonyOS NEXT (5.0+) makin tertutup — ProjectMenu mungkin butuh **Settings → About phone → tap Version 7x** untuk enable developer.
- Alternatif tanpa kode: **Settings → About phone / Battery → Battery health**.

[← harmonyos/README](README.md) | [🏠 Beranda](../README.md)
