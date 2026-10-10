# Kode Feature Phone — Nokia / HMD / KaiOS ☎️

> Nomor 1 yang paling gampang diingat: `*#06#`. Nomor 2 yang paling bahaya: `*#7370#` — jangan coba-coba!

## Cara Pakai

Buka dialer → ketik kodenya → tap Panggil (atau otomatis kebuka).

## Yang Jalan di Semua Feature Phone (Universal)

| Kode | Fungsinya | Contoh |
|---|---|---|
| `*#06#` | IMEI | Wajib cek kalau beli HP bekas |
| `*#21#` `*#62#` `##002#` | Pengalihan panggilan | → [umum/01-kode-ussd-mmi-universal.md](../umum/01-kode-ussd-mmi-universal.md) |
| `*#43#` `*43#` | Call waiting |  |

## Kode Khas Nokia / HMD (S30 / S30+ / KaiOS)

| Kode | Fungsinya | Risiko | Contoh & manfaat |
|---|---|---|---|
| `*#0000#` | Firmware & model | Aman | Cek versi KaiOS atau model Nokia 105 4G. Nongol `V 12.34.56`. |
| `*#06#` | IMEI | Aman |  |
| `*#92702689#` (`*#war0anty#`) | Warranty & life timer | Aman | Total jam pakai HP sejak pabrik. Cocok buat cek HP bekas — life timer 00:12:30 berarti masih baru banget. |
| `*#7780#` | **Soft reset** | ⚠️ Hati-hati | Balikin setting pabrik **tanpa hapus data**. Minta kode `12345`. Contoh: Nokia lemot → coba soft reset dulu. |
| `*#7370#` | **Hard reset / format** | ⛔ Bahaya | **Hapus semua data + format total!** Minta kode `12345`. Jangan iseng — data hilang permanen. |

## KaiOS (Nokia 8110 4G, 2720 Flip, dll)

- `*#06#` dan `*#0000#` jalan.
- `*#*#4636#*#*` nggak jalan — KaiOS bukan Android.
- Cek info lewat Settings → Device → Device Information.

## HP Jadul Lain

- Samsung jadul: `*2767*3855#` = format total — bahaya, lihat [android/08-kode-berisiko-tinggi.md](../android/08-kode-berisiko-tinggi.md)
- Sony Ericsson jadul: `*#06#`, `*#0000#`, `*#7353273#` (versi).

> Trik hafalin: `0000` = tentang HP, `7780` = soft (lebih lembut), `7370` = hard (keras — format). Lengkapnya di [umum/03-tips-mengingat-kode.md](../umum/03-tips-mengingat-kode.md).

[← feature-phone/README](README.md) | [🏠 Beranda](../README.md)
