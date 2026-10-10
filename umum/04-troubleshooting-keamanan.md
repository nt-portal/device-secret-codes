# Umum — Troubleshooting & Keamanan (Semua HP)

## Kode Tidak Merespon

| Gejala | Penyebab | Solusi |
|---|---|---|
| Ketik kode terakhir tidak muncul apa-apa | Bukan dialer bawaan / diblokir vendor (Android 12+ / iOS) | Android: pakai **Phone bawaan** / app *Force LTE Only*; iPhone: update iOS |
| `Connection problem / MMI invalid` | Sinyal lemah / salah ketik `*`/`#` | Airplane 5 dtk → coba lagi; cek penulisan |
| `*#*#4636#*#*` tidak buka | Google/vendor disable | Shortcut app — lihat [android/01-cara-menggunakan.md](../android/01-cara-menggunakan.md) |
| Field Test tidak buka (iPhone/HarmonyOS) | iOS/EMUI lama | Update OS |
| `*#0*#` tidak jalan (Samsung/Feature Phone) | Region/Go firmware disable | Samsung Members → Diagnostics; Nokia: `*#0000#` cek model |

## Keamanan & Privasi (Semua HP — Super Penting)

- **Jangan sebar IMEI** (`*#06#`) — rawan kloning. Cek resmi Kemenperin/bea cukai saja.
- **Jangan ketik kode dari orang asing** — `**21*08xxxx#` = aktifkan alihan ke penipu! Verifikasi `*#21#`.
- Alihan ke **voicemail operator** = normal, bukan sadap.
- Backup sebelum otak-atik reset: Android `*#*#7780#*#*`, Nokia `*#7370#`, iOS Reset Network Settings.

[← 03 Tips Menghafal](03-tips-mengingat-kode.md) | [→ 05 Referensi](05-referensi.md)
