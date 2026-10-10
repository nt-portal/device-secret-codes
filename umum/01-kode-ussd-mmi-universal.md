# Kode USSD / MMI Universal — Jalan di Semua HP 🌍

> Diproses sama jaringan operator GSM/4G/5G — jadi mau pakai Android, iPhone, HarmonyOS, atau Nokia jadul, semuanya bisa. Jangan lupa **tap Panggil** setelah ketik.

## Pengalihan Panggilan (Call Forwarding)

| Kode | Fungsinya | Keterangan |
|---|---|---|
| `*#21#` | Cek pengalihan semua panggilan | Yang unconditional — berdering pun langsung diteruskan |
| `*#61#` | Cek “nggak dijawab” | Diteruskan kalau nggak diangkat ~20–30 detik |
| `*#62#` | Cek “nggak terjangkau / HP mati” | Diteruskan pas HP mati atau nggak ada sinyal |
| `*#67#` | Cek “sibuk” | Diteruskan kalau kamu tolak atau lagi sibuk |
| `*#004#` | Cek semua pengalihan bersyarat | Sekaligus `*#61#` + `*#62#` + `*#67#` |
| `*#002#` | Cek semua pengalihan |  |
| `##002#` | **Hapus semua pengalihan** | Reset langsung di server operator |
| `##61#` / `##62#` / `##67#` | Hapus per kondisi |  |

## Call Waiting & Sembunyikan Nomor (CLIR)

| Kode | Fungsinya |
|---|---|
| `*#43#` | Cek call waiting |
| `*43#` / `#43#` | Aktifin / matiin call waiting |
| `*#31#` | Cek status sembunyikan nomor |
| `*31#` / `#31#` | Aktifin / matiin sembunyikan nomor permanen |
| `*31#<nomor>` | Nelpon sekali dengan nomor kesembunyi |
| `#31#<nomor>` | Nelpon sekali dengan nomor kelihatan |

## Identitas & Jaringan

| Kode | Fungsinya | Catatan |
|---|---|---|
| `*#06#` | IMEI | Jalan di semua HP, tanpa SIM pun bisa |
| `*#07#` | SAR / regulasi |  |
| `*3001#12345#*` | Field Test (iOS) | → [ios/02-field-test-mode.md](../ios/02-field-test-mode.md) |
| `*#*#4636#*#*` | Phone Info (Android) | → [android/05-jaringan-seluler.md](../android/05-jaringan-seluler.md) |

[← umum/README](README.md) | [Lanjut ke Contoh Kasus →](02-contoh-kasus-praktis.md)
