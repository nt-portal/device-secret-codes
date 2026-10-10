# Kode Feature Phone — Nokia / HMD / KaiOS ☎️

> Kode nomor satu yang paling mudah diingat: `*#06#`. Kode nomor dua yang paling berbahaya: `*#7370#` — jangan dicoba tanpa keperluan!

## Cara Penggunaan

Buka dialer → ketik kode → ketuk Panggil (atau akan terbuka otomatis).

## Kode Universal (Berfungsi di Feature Phone)

| Kode | Fungsi | Contoh |
|---|---|---|
| `*#06#` | IMEI | Wajib diperiksa saat membeli HP bekas |
| `*#21#` `*#62#` `##002#` | Pengalihan panggilan | → [umum/01-kode-ussd-mmi-universal.md](../umum/01-kode-ussd-mmi-universal.md) |
| `*#43#` `*43#` | Call waiting |  |

## Kode Khas Nokia / HMD (S30 / S30+ / KaiOS)

| Kode | Fungsi | Risiko | Contoh & manfaat |
|---|---|---|---|
| `*#0000#` | Firmware & model | Aman | Memeriksa versi KaiOS atau model Nokia 105 4G. Akan menampilkan `V 12.34.56`. |
| `*#06#` | IMEI | Aman |  |
| `*#92702689#` (`*#war0anty#`) | Warranty & life timer | Aman | Total jam pemakaian HP sejak dari pabrik. Cocok untuk memeriksa HP bekas — life timer 00:12:30 berarti masih sangat baru. |
| `*#7780#` | **Soft reset** | ⚠️ Hati-hati | Mengembalikan pengaturan pabrik **tanpa menghapus data**. Meminta kode keamanan (default `12345`). Contoh: Nokia terasa lambat → coba soft reset terlebih dahulu. |
| `*#7370#` | **Hard reset / format** | ⛔ Bahaya | **Menghapus semua data dan format total!** Meminta kode `12345`. Jangan dicoba secara iseng — data akan hilang permanen. |

## KaiOS (Nokia 8110 4G, 2720 Flip, dll)

- `*#06#` dan `*#0000#` berfungsi.
- `*#*#4636#*#*` tidak berfungsi — KaiOS bukan Android.
- Pemeriksaan informasi melalui Settings → Device → Device Information.

## HP Jadul Lain

- Samsung lama: `*2767*3855#` = format total — berbahaya, lihat [android/08-kode-berisiko-tinggi.md](../android/08-kode-berisiko-tinggi.md)
- Sony Ericsson lama: `*#06#`, `*#0000#`, `*#7353273#` (versi).

> Tips menghafal: `0000` = tentang perangkat, `7780` = soft (lebih ringan), `7370` = hard (keras — format total). Selengkapnya di [umum/03-tips-mengingat-kode.md](../umum/03-tips-mengingat-kode.md).

[← feature-phone/README](README.md) | [🏠 Beranda](../README.md)
