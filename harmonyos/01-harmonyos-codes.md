# Kode HarmonyOS / Huawei EMUI 🔧

> Berlaku buat Huawei P/Mate/Nova dan Honor lama (EMUI) sampai HarmonyOS NEXT. Pakai **Phone bawaan Huawei** ya.

## Cara Pakai

Phone → Keypad → ketik kodenya → otomatis kebuka atau tap Panggil. Kalau nggak jalan di HarmonyOS 3+, coba pakai dialer bawaan jangan yang pihak ketiga.

## Kode Khas Huawei / HarmonyOS

| Kode | Fungsinya | Contoh & manfaatnya |
|---|---|---|
| `*#*#2846579#*#*` | **ProjectMenu** (menu utamanya Huawei) | Ini yang paling penting. Di dalamnya ada Battery, Network Information Query, Veneer Info, Software Upgrade — bisa cek kesehatan baterai tanpa bongkar. |
| `*#*#1357946#*#*` | SN & Product ID | Buat unlock bootloader/service. Contoh: catat SN buat klaim garansi. |
| `*#06#` | IMEI | Universal — buat cek Kemenperin. |
| `*#07#` | SAR / regulasi |  |
| `*#*#6130#*#*` | Testing (varian) | Info jaringan di beberapa EMUI. |
| `*#*#0000#*#*` | About / version | Liat versi HarmonyOS & patch. |

## Yang Universal (Jalan Juga di HarmonyOS)

` *#21#` `##002#` `*#43#` `*#31#` — semuanya jalan karena diproses operator, bukan OS. Detailnya di [umum/01-kode-ussd-mmi-universal.md](../umum/01-kode-ussd-mmi-universal.md).

> Catatan: HarmonyOS NEXT makin tertutup — kadang ProjectMenu butuh aktifin developer dulu via Settings → About phone → tap Version 7x. Alternatif tanpa kode: Settings → About phone / Battery → Battery health.

[← harmonyos/README](README.md) | [🏠 Beranda](../README.md)
