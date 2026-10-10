# Secret Dial Codes — Semua HP, Satu Tempat 📱

> Hai, selamat datang! Repo ini ngumpulin semua kode dial rahasia (secret codes, USSD, MMI) yang kepake di **Android, iPhone, HarmonyOS, sampai HP jadul Nokia/KaiOS** — jadi kamu nggak perlu muter-muter nyari di forum lagi. Semua udah dirangkum rapi, lengkap dengan contoh biar langsung paham.

> ⚠️ Catatan jujur: nggak semua kode bakal jalan di HP kamu. Tergantung merek, versi OS, dan operator. Beberapa kode juga bisa ngerubah setting atau bahkan ngapus data — jadi bacanya pelan-pelan ya, jangan asal coba.

---

## Peta Folder — Biar Nggak Nyasar 🗺️

```text
.
├── LICENSE
├── README.md                    ← kamu di sini
│
├── android/                     ← buat pengguna Android
│   ├── README.md
│   ├── 01-cara-menggunakan.md           # bedanya USSD vs kode internal, cara ketiknya gimana
│   ├── 02-informasi-perangkat.md        # IMEI, SAR, RAM, MAC address
│   ├── 03-diagnostik-system.md          # FCM, usage stats, check update
│   ├── 04-tes-hardware.md               # tes layar, sensor, speaker, GPS, kamera
│   ├── 05-jaringan-seluler.md           # ServiceMode, kunci band, VoLTE
│   ├── 06-pengalihan-panggilan.md       # *#21#, ##002#, *#43#
│   ├── 07-kode-vendor.md                # Samsung, Xiaomi, OPPO, Vivo, OnePlus, Sony, Pixel
│   └── 08-kode-berisiko-tinggi.md       # yang bahaya — jangan iseng dicoba
│
├── ios/                         ← buat pengguna iPhone / iPad
│   ├── README.md
│   ├── 01-cara-menggunakan-ios.md       # cara pakai di iPhone (beda sama Android)
│   ├── 02-field-test-mode.md            # *3001#12345#* — cek sinyal RSRP/SINR/Band
│   ├── 03-kode-iphone-lainnya.md        # IMEI, CLIR, SMSC, dll
│   └── 04-tips-ios.md                   # kalau kode nggak ada, ceknya lewat Settings
│
├── harmonyos/                   ← buat Huawei HarmonyOS / EMUI
│   ├── README.md
│   └── 01-harmonyos-codes.md            # ProjectMenu khas Huawei
│
├── feature-phone/               ← buat HP jadul — Nokia, HMD, KaiOS
│   ├── README.md
│   └── 01-feature-phone-codes.md        # *#0000#, *#7780#, life timer
│
└── umum/                        ← yang jalan di semua HP & operator
    ├── README.md
    ├── 01-kode-ussd-mmi-universal.md    # GSM: *#21#, ##002#, *#43#, *#31#, *#06#
    ├── 02-contoh-kasus-praktis.md       # beli HP bekas, cek sadap, cek IMEI
    ├── 03-tips-mengingat-kode.md        # trik hafalin kode biar nempel
    ├── 04-troubleshooting-keamanan.md   # kalau MMI error, tips aman IMEI
    └── 05-referensi.md                  # sumber + lisensi
```

---

## Mau Mulai Dari Mana? 🚀

| Kamu pakai HP... | Buka ini dulu ya |
|---|---|
| Android Samsung / Xiaomi / OPPO / Realme / Vivo | [android/README.md](android/README.md) |
| iPhone / iPad | [ios/README.md](ios/README.md) |
| Huawei HarmonyOS / EMUI | [harmonyos/README.md](harmonyos/README.md) |
| Nokia / HMD / HP jadul KaiOS | [feature-phone/README.md](feature-phone/README.md) |
| Kode operator yang jalan di semua HP | [umum/01-kode-ussd-mmi-universal.md](umum/01-kode-ussd-mmi-universal.md) |
| Mau cek HP bekas / sinyal lemah / curiga disadap | [umum/02-contoh-kasus-praktis.md](umum/02-contoh-kasus-praktis.md) |
| Susah ngafalin kode | [umum/03-tips-mengingat-kode.md](umum/03-tips-mengingat-kode.md) |
| Kode nggak jalan / muncul MMI invalid | [umum/04-troubleshooting-keamanan.md](umum/04-troubleshooting-keamanan.md) |

---

## Kode yang Paling Sering Dipakai ⭐

| Buat apa | Kodenya | Lihat di |
|---|---|---|
| Cek IMEI | `*#06#` | [umum/01-kode-ussd-mmi-universal.md](umum/01-kode-ussd-mmi-universal.md) |
| Cek panggilan dialihkan | `*#21#` → Panggil | [umum/01-kode-ussd-mmi-universal.md](umum/01-kode-ussd-mmi-universal.md) |
| Hapus semua pengalihan | `##002#` → Panggil | [umum/01-kode-ussd-mmi-universal.md](umum/01-kode-ussd-mmi-universal.md) |
| Cek call waiting | `*#43#` | [umum/01-kode-ussd-mmi-universal.md](umum/01-kode-ussd-mmi-universal.md) |
| Field Test iPhone | `*3001#12345#*` | [ios/02-field-test-mode.md](ios/02-field-test-mode.md) |
| Info lengkap Android | `*#*#4636#*#*` | [android/03-diagnostik-system.md](android/03-diagnostik-system.md) |
| Tes hardware Samsung | `*#0*#` | [android/07-kode-vendor.md](android/07-kode-vendor.md) |
| Menu CIT Xiaomi | `*#*#6484#*#*` | [android/07-kode-vendor.md](android/07-kode-vendor.md) |
| ProjectMenu Huawei | `*#*#2846579#*#*` | [harmonyos/01-harmonyos-codes.md](harmonyos/01-harmonyos-codes.md) |
| Info Nokia jadul | `*#0000#` | [feature-phone/01-feature-phone-codes.md](feature-phone/01-feature-phone-codes.md) |

---

## Susah Ngafalin? Tenang 😊

Udah dibikinin trik mnemonic biar gampang nempel di kepala — cek [umum/03-tips-mengingat-kode.md](umum/03-tips-mengingat-kode.md).

## Lisensi 📜

Bebas pakai, modifikasi, dan sebar ulang — MIT / CC-BY 4.0. Lihat [LICENSE](LICENSE) dan [umum/05-referensi.md](umum/05-referensi.md).
