# Feature Phone — Kode Lengkap (Nokia / HMD / KaiOS)

> Nomor 1 paling hafal: `*#06#`. Nomor 2 paling bahaya: `*#7370#` — jangan coba!

## Cara Pakai

Buka **dialer** → ketik → **tap Panggil** (atau auto). Semua butuh dialer bawaan.

## Kode Universal (Jalan di Feature Phone)

| Kode | Fungsi | Contoh |
|---|---|---|
| `*#06#` | IMEI | **Wajib cek** beli HP bekas. |
| `*#21#` `*#62#` `##002#` | Alihan panggilan | → [umum/01-kode-ussd-mmi-universal.md](../umum/01-kode-ussd-mmi-universal.md) |
| `*#43#` `*43#` | Call waiting | |

## Kode Nokia / HMD (S30 / S30+ / KaiOS)

| Kode | Fungsi | Tingkat | Contoh / Manfaat |
|---|---|---|---|
| `*#0000#` | Firmware & model | Aman | **Contoh:** Cek versi KaiOS 2.5.4 vs 3.0; cek model Nokia 105 4G. Muncul `V 12.34.56`. |
| `*#06#` | IMEI | Aman | |
| `*#92702689#` (`*#war0anty#`) | Warranty & life timer | Aman | Total jam pemakaian HP sejak pabrik. **Contoh:** cek HP bekas Nokia — life timer 00:12:30 = hampir baru. |
| `*#7780#` | **Soft reset** (restore settings) | ⚠️ Tinggi | Kembalikan setting pabrik **tanpa hapus data**. Minta kode keamanan (default `12345`). **Contoh:** HP Nokia lemot → soft reset dulu sebelum hard reset. |
| `*#7370#` | **Hard reset / format** | ⛔ Kritis | **Hapus semua data + format!** Minta kode `12345`. **JANGAN coba iseng — data hilang permanen.** |

## KaiOS (Nokia 8110 4G, 2720 Flip, dll)

- `*#06#`, `*#0000#` jalan.
- `*#*#4636#*#*` **tidak** jalan — KaiOS bukan Android.
- Cek info: **Settings → Device → Device Information**.

## HP Jadul Lain (Samsung / Sony Ericsson / LG jadul)

- `*2767*3855#` (Samsung jadul) = format total — **bahaya**, lihat [android/08-kode-berisiko-tinggi.md](../android/08-kode-berisiko-tinggi.md)
- Sony Ericsson: `*#06#`, `*#0000#`, `*#7353273#` (versi).

## Mnemonic Feature Phone

- `0000` = nol-nol-nol-nol = versi "nol" alias tentang HP.
- `7780` = soft (8 > 7, lebih lembut dari hard).
- `7370` = hard (73-70 keras — hard reset).

→ Tips hafal lengkap: [umum/03-tips-mengingat-kode.md](../umum/03-tips-mengingat-kode.md)

[← feature-phone/README](README.md) | [🏠 Beranda](../README.md)
