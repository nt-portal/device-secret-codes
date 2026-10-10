# Secret Dial Codes — Semua HP, Satu Tempat 📱

> Selamat datang! Repositori ini mengumpulkan semua kode dial rahasia (secret codes, USSD, MMI) yang digunakan di **Android, iPhone (iOS), HarmonyOS, hingga HP feature phone seperti Nokia dan KaiOS**. Semua dirangkum dalam satu tempat — terstruktur, lengkap dengan penjelasan dan contoh agar mudah dipahami dan langsung bisa dipraktikkan.

> ⚠️ Penting: Tidak semua kode akan berfungsi di setiap perangkat. Keberhasilan tergantung pada merek, versi sistem operasi, dan operator yang digunakan. Beberapa kode juga dapat mengubah pengaturan atau menghapus data, jadi harap digunakan dengan hati-hati.

## ⭐ Baru Ditambahkan

**Dua panduan edukasi baru di dalam repositori ini:**

- **Android Secret Codes & Call Forwarding Security** — panduan lengkap mengenai kode dial Android, kode MMI/USSD, pengalihan panggilan, layanan operator, diagnostik perangkat, risiko penyalahgunaan, dan cara melindungi privasi.
- **Android Call Forwarding & Security Recovery** — panduan pemulihan untuk memeriksa pengalihan panggilan, menonaktifkan layanan yang tidak dikenal, serta langkah mengamankan Android.

Kedua panduan tersedia sebagai dokumen mandiri di folder [`umum/security/`](umum/security/) dan juga diringkas di README ini.

---

## Peta Folder 🗺️

```text
.
├── LICENSE
├── README.md                              ← Anda di sini (indeks utama)
│
├── android/                               ← Untuk pengguna Android
│   ├── README.md
│   ├── 01-cara-menggunakan.md
│   ├── 02-informasi-perangkat.md
│   ├── 03-diagnostik-system.md
│   ├── 04-tes-hardware.md
│   ├── 05-jaringan-seluler.md
│   ├── 06-pengalihan-panggilan.md
│   ├── 07-kode-vendor.md
│   └── 08-kode-berisiko-tinggi.md
│
├── ios/                                   ← Untuk pengguna iPhone / iPad
│   ├── README.md
│   ├── 01-cara-menggunakan-ios.md
│   ├── 02-field-test-mode.md
│   ├── 03-kode-iphone-lainnya.md
│   └── 04-tips-ios.md
│
├── harmonyos/                             ← Untuk Huawei HarmonyOS / EMUI
│   ├── README.md
│   └── 01-harmonyos-codes.md
│
├── feature-phone/                         ← Untuk HP feature phone — Nokia, HMD, KaiOS
│   ├── README.md
│   └── 01-feature-phone-codes.md
│
└── umum/                                  ← Berlaku untuk semua HP & operator
    ├── README.md
    ├── 01-kode-ussd-mmi-universal.md
    ├── 02-contoh-kasus-praktis.md
    ├── 03-tips-mengingat-kode.md
    ├── 04-troubleshooting-keamanan.md
    ├── 05-referensi.md
    └── security/                          ← ⭐ Panduan keamanan baru
        ├── README.md
        ├── 01-android-secret-codes-call-forwarding-security.md
        └── 02-android-call-forwarding-security-recovery.md
```

---

## Mulai dari Mana? 🚀

| Anda menggunakan... | Silakan buka... |
|---|---|
| Android (Samsung / Xiaomi / OPPO / Realme / Vivo) | [android/README.md](android/README.md) |
| iPhone / iPad | [ios/README.md](ios/README.md) |
| Huawei HarmonyOS / EMUI | [harmonyos/README.md](harmonyos/README.md) |
| Nokia / HMD / HP KaiOS | [feature-phone/README.md](feature-phone/README.md) |
| Kode operator yang berlaku di semua HP | [umum/01-kode-ussd-mmi-universal.md](umum/01-kode-ussd-mmi-universal.md) |
| Ingin memahami pengalihan panggilan & risikonya | [umum/security/01-android-secret-codes-call-forwarding-security.md](umum/security/01-android-secret-codes-call-forwarding-security.md) |
| Ingin memulihkan pengalihan & mengamankan HP | [umum/security/02-android-call-forwarding-security-recovery.md](umum/security/02-android-call-forwarding-security-recovery.md) |
| Keperluan cek HP bekas / sinyal lemah / curiga disadap | [umum/02-contoh-kasus-praktis.md](umum/02-contoh-kasus-praktis.md) |
| Kesulitan menghafal kode | [umum/03-tips-mengingat-kode.md](umum/03-tips-mengingat-kode.md) |
| Kode tidak berfungsi / muncul MMI invalid | [umum/04-troubleshooting-keamanan.md](umum/04-troubleshooting-keamanan.md) |

---

## Kode yang Paling Sering Digunakan ⭐

| Keperluan | Kode | Lihat di |
|---|---|---|
| Mengecek IMEI | `*#06#` | [umum/01-kode-ussd-mmi-universal.md](umum/01-kode-ussd-mmi-universal.md) |
| Mengecek pengalihan panggilan | `*#21#` → Panggil | [umum/security/01-android-secret-codes-call-forwarding-security.md](umum/security/01-android-secret-codes-call-forwarding-security.md) |
| Menghapus semua pengalihan | `##002#` → Panggil | [umum/security/02-android-call-forwarding-security-recovery.md](umum/security/02-android-call-forwarding-security-recovery.md) |
| Mengecek call waiting | `*#43#` | [umum/01-kode-ussd-mmi-universal.md](umum/01-kode-ussd-mmi-universal.md) |
| Field Test iPhone | `*3001#12345#*` | [ios/02-field-test-mode.md](ios/02-field-test-mode.md) |
| Informasi lengkap Android | `*#*#4636#*#*` | [android/03-diagnostik-system.md](android/03-diagnostik-system.md) |
| Tes hardware Samsung | `*#0*#` | [android/07-kode-vendor.md](android/07-kode-vendor.md) |
| Menu CIT Xiaomi | `*#*#6484#*#*` | [android/07-kode-vendor.md](android/07-kode-vendor.md) |
| ProjectMenu Huawei | `*#*#2846579#*#*` | [harmonyos/01-harmonyos-codes.md](harmonyos/01-harmonyos-codes.md) |
| Informasi Nokia feature phone | `*#0000#` | [feature-phone/01-feature-phone-codes.md](feature-phone/01-feature-phone-codes.md) |

---

## Panduan Keamanan Baru 🛡️

Bagian ini diringkas dari dua dokumen di [`umum/security/`](umum/security/README.md):

- Pahami bahwa `*#21#` hanya memeriksa status pengalihan yang dilaporkan jaringan — bukan pendeteksi penyadapan universal.
- Pengalihan ke nomor pesan suara operator adalah hal normal, bukan otomatis indikasi penyalahgunaan.
- Tidak ada satu kode MMI universal yang dapat mengalihkan semua SMS di semua operator — penerusan SMS terjadi lewat aplikasi, sinkronisasi, atau layanan operator tertentu.
- Selalu baca pesan hasil kode sebelum bertindak, dan gunakan kanal resmi operator untuk verifikasi.
- Risiko terbesar justru dari aplikasi dengan izin SMS/notifikasi/aksesibilitas dan dari kode reset di perangkat lama — bukan dari kode diagnostik biasa.

Selengkapnya: [Panduan Lengkap](umum/security/01-android-secret-codes-call-forwarding-security.md) dan [Panduan Pemulihan](umum/security/02-android-call-forwarding-security-recovery.md).

---

## Kesulitan Menghafal Kode? 😊

Sudah disiapkan teknik mnemonic agar kode lebih mudah diingat — lihat [umum/03-tips-mengingat-kode.md](umum/03-tips-mengingat-kode.md).

## Lisensi 📜

Bebas digunakan, dimodifikasi, dan disebarluaskan — berlisensi MIT / CC-BY 4.0. Lihat [LICENSE](LICENSE) dan [umum/05-referensi.md](umum/05-referensi.md).
