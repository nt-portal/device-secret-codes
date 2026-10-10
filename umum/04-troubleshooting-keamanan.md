# Troubleshooting & Keamanan — Semua HP 🔧🔒

## Kalau Kode Nggak Jalan

| Gejalanya | Penyebabnya | Solusinya |
|---|---|---|
| Ketik kode terakhir nggak muncul apa-apa | Bukan dialer bawaan / diblokir vendor (Android 12+ / iOS) | Pakai **Phone bawaan**; di Android coba *Activity Launcher / Force LTE Only* |
| `Connection problem / MMI invalid` | Sinyal lemah / salah ketik `*`/`#` | Airplane mode 5 detik → coba lagi; cek penulisan |
| `*#*#4636#*#*` nggak kebuka | Google/vendor di-disable | Pakai app shortcut — lihat [android/01-cara-menggunakan.md](../android/01-cara-menggunakan.md) |
| Field Test nggak kebuka (iPhone/HarmonyOS) | iOS/EMUI lama | Update OS-nya dulu |
| `*#0*#` nggak jalan (Samsung) | Region/Go firmware | Pakai Samsung Members → Diagnostics |

## Keamanan & Privasi — Penting Banget!

- **Jangan sebar IMEI** (`*#06#`) di medsos — rawan dikloning.
- **Jangan asal ketik kode dari orang asing** — `**21*08xxxx#` itu ngaktifin pengalihan ke penipu! Verifikasi dulu pakai `*#21#`.
- Pengalihan ke **voicemail operator** itu normal, bukan disadap.
- Backup dulu sebelum otak-atik reset — entah `*#*#7780#*#*` (Android), `*#7370#` (Nokia), atau Reset Network Settings (iOS).

[← Tips Menghafal](03-tips-mengingat-kode.md) | [Lanjut ke Referensi →](05-referensi.md)
