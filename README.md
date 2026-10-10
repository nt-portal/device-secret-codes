# Secret Dial Codes — Semua HP, Satu Tempat 📱

> Selamat datang! Repositori ini mengumpulkan semua kode dial rahasia (secret codes, USSD, MMI) yang digunakan di **Android, iPhone (iOS), HarmonyOS, hingga HP feature phone seperti Nokia dan KaiOS**. Semua dirangkum dalam satu tempat — terstruktur, lengkap dengan penjelasan dan contoh agar mudah dipahami dan langsung bisa dipraktikkan.

> ⚠️ Penting: Tidak semua kode akan berfungsi di setiap perangkat. Keberhasilan tergantung pada merek, versi sistem operasi, dan operator yang digunakan. Beberapa kode juga dapat mengubah pengaturan atau menghapus data, jadi harap digunakan dengan hati-hati.

---

## Peta Folder 🗺️

```text
.
├── LICENSE
├── README.md                    ← Anda di sini
│
├── android/                     ← Untuk pengguna Android
│   ├── README.md
│   ├── 01-cara-menggunakan.md           # Perbedaan USSD vs kode internal & cara menggunakannya
│   ├── 02-informasi-perangkat.md        # IMEI, SAR, RAM, MAC address
│   ├── 03-diagnostik-system.md          # FCM, usage stats, pemeriksaan pembaruan
│   ├── 04-tes-hardware.md               # Pengujian layar, sensor, speaker, GPS, kamera
│   ├── 05-jaringan-seluler.md           # ServiceMode, penguncian band, VoLTE
│   ├── 06-pengalihan-panggilan.md       # *#21#, ##002#, *#43#
│   ├── 07-kode-vendor.md                # Samsung, Xiaomi, OPPO, Vivo, OnePlus, Sony, Pixel
│   └── 08-kode-berisiko-tinggi.md       # Kode berisiko tinggi — jangan dicoba sembarangan
│
├── ios/                         ← Untuk pengguna iPhone / iPad
│   ├── README.md
│   ├── 01-cara-menggunakan-ios.md       # Cara menggunakan kode di iPhone
│   ├── 02-field-test-mode.md            # *3001#12345#* — pemeriksaan sinyal RSRP/SINR/Band
│   ├── 03-kode-iphone-lainnya.md        # IMEI, CLIR, SMSC, dan lainnya
│   └── 04-tips-ios.md                   # Alternatif pemeriksaan melalui menu Settings
│
├── harmonyos/                   ← Untuk Huawei HarmonyOS / EMUI
│   ├── README.md
│   └── 01-harmonyos-codes.md            # ProjectMenu khas Huawei
│
├── feature-phone/               ← Untuk HP feature phone — Nokia, HMD, KaiOS
│   ├── README.md
│   └── 01-feature-phone-codes.md        # *#0000#, *#7780#, life timer
│
└── umum/                        ← Berlaku untuk semua HP & operator
    ├── README.md
    ├── 01-kode-ussd-mmi-universal.md    # GSM: *#21#, ##002#, *#43#, *#31#, *#06#
    ├── 02-contoh-kasus-praktis.md       # Studi kasus: HP bekas, pengecekan sadap, IMEI
    ├── 03-tips-mengingat-kode.md        # Teknik mengingat kode dengan mudah
    ├── 04-troubleshooting-keamanan.md   # Mengatasi MMI invalid & tips keamanan IMEI
    └── 05-referensi.md                  # Daftar sumber dan lisensi
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
| Keperluan cek HP bekas / sinyal lemah / curiga disadap | [umum/02-contoh-kasus-praktis.md](umum/02-contoh-kasus-praktis.md) |
| Kesulitan menghafal kode | [umum/03-tips-mengingat-kode.md](umum/03-tips-mengingat-kode.md) |
| Kode tidak berfungsi / muncul MMI invalid | [umum/04-troubleshooting-keamanan.md](umum/04-troubleshooting-keamanan.md) |

---

## Kode yang Paling Sering Digunakan ⭐

| Keperluan | Kode | Lihat di |
|---|---|---|
| Mengecek IMEI | `*#06#` | [umum/01-kode-ussd-mmi-universal.md](umum/01-kode-ussd-mmi-universal.md) |
| Mengecek pengalihan panggilan | `*#21#` → Panggil | [umum/01-kode-ussd-mmi-universal.md](umum/01-kode-ussd-mmi-universal.md) |
| Menghapus semua pengalihan | `##002#` → Panggil | [umum/01-kode-ussd-mmi-universal.md](umum/01-kode-ussd-mmi-universal.md) |
| Mengecek call waiting | `*#43#` | [umum/01-kode-ussd-mmi-universal.md](umum/01-kode-ussd-mmi-universal.md) |
| Field Test iPhone | `*3001#12345#*` | [ios/02-field-test-mode.md](ios/02-field-test-mode.md) |
| Informasi lengkap Android | `*#*#4636#*#*` | [android/03-diagnostik-system.md](android/03-diagnostik-system.md) |
| Tes hardware Samsung | `*#0*#` | [android/07-kode-vendor.md](android/07-kode-vendor.md) |
| Menu CIT Xiaomi | `*#*#6484#*#*` | [android/07-kode-vendor.md](android/07-kode-vendor.md) |
| ProjectMenu Huawei | `*#*#2846579#*#*` | [harmonyos/01-harmonyos-codes.md](harmonyos/01-harmonyos-codes.md) |
| Informasi Nokia feature phone | `*#0000#` | [feature-phone/01-feature-phone-codes.md](feature-phone/01-feature-phone-codes.md) |

---

## Kesulitan Menghafal Kode? 😊

Sudah disiapkan teknik mnemonic agar kode lebih mudah diingat — lihat [umum/03-tips-mengingat-kode.md](umum/03-tips-mengingat-kode.md).

## Lisensi 📜

Bebas digunakan, dimodifikasi, dan disebarluaskan — berlisensi MIT / CC-BY 4.0. Lihat [LICENSE](LICENSE) dan [umum/05-referensi.md](umum/05-referensi.md).
