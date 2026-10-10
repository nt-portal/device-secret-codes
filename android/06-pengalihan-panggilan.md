# Android — Pengalihan Panggilan (Call Forwarding)

> Diproses operator — wajib tekan **Panggil**.

| Kode | Fungsi |
|---|---|
| `*#21#` | Cek alihan semua panggilan (unconditional) |
| `*#61#` | Cek alihan “tidak dijawab” |
| `*#62#` | Cek alihan “tidak terjangkau / HP mati” |
| `*#67#` | Cek alihan “sibuk” |
| `*#004#` | Cek semua alihan bersyarat |
| `*#002#` | Cek semua alihan |
| `##002#` | **Hapus semua alihan** |
| `*#43#` | Cek call waiting |
| `*43#` / `#43#` | Aktifkan / matikan call waiting |

**Cek sadap?** `*#21#` → Panggil. Jika *Forwarded* ke nomor asing bukan voicemail operator → `##002#` → Panggil. Lihat juga [umum/01-kode-ussd-mmi-universal.md](../umum/01-kode-ussd-mmi-universal.md).

[← 05 Jaringan](05-jaringan-seluler.md) | [→ 07 Kode Vendor](07-kode-vendor.md)
