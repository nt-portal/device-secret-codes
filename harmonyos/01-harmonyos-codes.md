# Kode HarmonyOS / Huawei EMUI 🔧

> Berlaku untuk Huawei seri P/Mate/Nova dan Honor lama (EMUI) hingga HarmonyOS NEXT. Gunakan **aplikasi Phone bawaan Huawei**.

## Cara Penggunaan

Phone → Keypad → ketik kode → terbuka otomatis atau ketuk Panggil. Jika tidak berfungsi di HarmonyOS 3 ke atas, pastikan menggunakan dialer bawaan, bukan aplikasi pihak ketiga.

## Kode Khas Huawei / HarmonyOS

| Kode | Fungsi | Contoh & manfaat |
|---|---|---|
| `*#*#2846579#*#*` | **ProjectMenu** (menu utama Huawei) | Ini yang paling penting. Di dalamnya terdapat Battery, Network Information Query, Veneer Info, dan Software Upgrade — dapat memeriksa kesehatan baterai tanpa membongkar perangkat. |
| `*#*#1357946#*#*` | SN & Product ID | Untuk keperluan unlock bootloader/service. Contoh: mencatat SN untuk klaim garansi. |
| `*#06#` | IMEI | Universal — untuk pengecekan Kemenperin. |
| `*#07#` | SAR / regulasi |  |
| `*#*#6130#*#*` | Testing (varian) | Informasi jaringan di beberapa versi EMUI. |
| `*#*#0000#*#*` | About / version | Melihat versi HarmonyOS dan patch. |

## Kode Universal (Juga Berfungsi di HarmonyOS)

` *#21#` `##002#` `*#43#` `*#31#` — semuanya berfungsi karena diproses oleh operator, bukan sistem operasi. Detail lengkap di [umum/01-kode-ussd-mmi-universal.md](../umum/01-kode-ussd-mmi-universal.md).

> Catatan: HarmonyOS NEXT semakin tertutup — ProjectMenu terkadang memerlukan aktivasi mode developer melalui Settings → About phone → ketuk Version 7 kali. Alternatif tanpa kode: Settings → About phone / Battery → Battery health.

[← harmonyos/README](README.md) | [🏠 Beranda](../README.md)
