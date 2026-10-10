# Umum — Kode USSD / MMI Universal (Android + iOS)

> Diproses jaringan operator GSM/4G/5G — jalan di Android maupun iPhone. Semua butuh **tap Panggil**.

## Call Forwarding (Pengalihan Panggilan)

| Kode | Fungsi | Keterangan |
|---|---|---|
| `*#21#` | Cek alihan semua panggilan (unconditional) | Berdering pun langsung diteruskan |
| `*#61#` | Cek “tidak dijawab” | Diteruskan jika tidak diangkat ±20–30 dtk |
| `*#62#` | Cek “tidak terjangkau / HP mati” | Diteruskan saat HP mati / no service |
| `*#67#` | Cek “sibuk” | Diteruskan saat tolak/sibuk |
| `*#004#` | Cek semua alihan bersyarat | Sekaligus `*#61#`+`*#62#`+`*#67#` |
| `*#002#` | Cek semua alihan | |
| `##002#` | **Hapus semua alihan** | Reset di server operator |
| `##61#` / `##62#` / `##67#` | Hapus alihan per kondisi | |

## Call Waiting & CLIR

| Kode | Fungsi |
|---|---|
| `*#43#` | Cek call waiting |
| `*43#` / `#43#` | Aktif / mati call waiting |
| `*#31#` | Cek sembunyikan nomor (CLIR) |
| `*31#` / `#31#` | Aktif / mati sembunyikan nomor permanen |
| `*31#<nomor>` | Telpon sekali dengan nomor tersembunyi |
| `#31#<nomor>` | Telpon sekali dengan nomor terlihat |

## Identitas & Jaringan

| Kode | Fungsi | Catatan |
|---|---|---|
| `*#06#` | IMEI | Jalan di semua HP (tanpa/sim) |
| `*#07#` | SAR / regulasi | |
| `*3001#12345#*` | Field Test (iOS) | → [ios/02-field-test-mode.md](../ios/02-field-test-mode.md) |
| `*#*#4636#*#*` | Phone Info (Android) | → [android/05-jaringan-seluler.md](../android/05-jaringan-seluler.md) |

[← umum/README](README.md) | [→ 02 Contoh Kasus](02-contoh-kasus-praktis.md)
