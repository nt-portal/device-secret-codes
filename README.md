# 📱 Secret Dial Codes — Super Lengkap (Semua HP & Smartphone)

> **Satu titik, semua HP ada.** Android, iPhone (iOS), HarmonyOS/Huawei, Feature Phone (Nokia/HMD, KaiOS), sampai kode **Universal GSM/USSD** yang jalan di semua operator. Lengkap, terstruktur per bab, mudah diingat, penuh contoh praktis.

> ⚠️ **Peringatan:** Tidak semua kode jalan di setiap merek / OS / operator. Kode berisiko (reset/format) hanya pakai kalau paham dampaknya. Risiko tanggung sendiri.

---

## 🗺️ Peta Struktur — Semua HP Dalam Satu Repo

```
.
├── LICENSE
├── README.md                    ← kamu di sini (indeks super-lengkap)
│
├── android/                     ← 8 modul Android
│   ├── README.md
│   ├── 01-cara-menggunakan.md           # jenis kode, cara ketik
│   ├── 02-informasi-perangkat.md        # IMEI, SAR, RAM, MAC
│   ├── 03-diagnostik-system.md          # FCM, usage stats
│   ├── 04-tes-hardware.md               # layar, sensor, audio, GPS
│   ├── 05-jaringan-seluler.md           # ServiceMode, band lock, VoLTE
│   ├── 06-pengalihan-panggilan.md       # *#21# ##002# *#43#
│   ├── 07-kode-vendor.md                # Samsung Xiaomi OPPO Vivo OnePlus Sony Pixel
│   └── 08-kode-berisiko-tinggi.md       # reset/format — bahaya
│
├── ios/                         ← 4 modul iPhone/iPad
│   ├── README.md
│   ├── 01-cara-menggunakan-ios.md       # beda Android vs iOS
│   ├── 02-field-test-mode.md            # *3001#12345#* — RSRP/SINR/Band/CA
│   ├── 03-kode-iphone-lainnya.md        # CLIR, SMSC, IMEI
│   └── 04-tips-ios.md                   # cek tanpa kode via Settings
│
├── harmonyos/                   ← 2 modul Huawei HarmonyOS
│   ├── README.md
│   └── 01-harmonyos-codes.md            # ProjectMenu, EMUI/HarmonyOS
│
├── feature-phone/               ← 2 modul HP biasa / KaiOS
│   ├── README.md
│   └── 01-feature-phone-codes.md        # Nokia/HMD, KaiOS, HP jadul
│
└── umum/                        ← 5 modul lintas semua HP & operator
    ├── README.md
    ├── 01-kode-ussd-mmi-universal.md    # GSM: *#21# ##002# *#43# *#31# *#06#
    ├── 02-contoh-kasus-praktis.md       # beli HP bekas, cek sadap, IMEI
    ├── 03-tips-mengingat-kode.md        # ✨ mnemonic & trik hafal cepat
    ├── 04-troubleshooting-keamanan.md   # MMI invalid, privasi IMEI
    └── 05-referensi.md                  # sumber & lisensi MIT/CC-BY
```

---

## 🚀 Mulai Dari Mana? (Pilih HP-mu)

| HP kamu... | Buka dulu... |
|---|---|
| **Android** Samsung / Xiaomi / OPPO / Realme / Vivo | [android/README.md](android/README.md) |
| **iPhone / iPad (iOS)** | [ios/README.md](ios/README.md) |
| **Huawei HarmonyOS / EMUI** | [harmonyos/README.md](harmonyos/README.md) |
| **Nokia / HMD / KaiOS / HP jadul** | [feature-phone/README.md](feature-phone/README.md) |
| **Kode operator (semua HP)** `*#21#` `##002#` `*#06#` | [umum/01-kode-ussd-mmi-universal.md](umum/01-kode-ussd-mmi-universal.md) |
| **Beli HP bekas / cek sadap / sinyal lemah** | [umum/02-contoh-kasus-praktis.md](umum/02-contoh-kasus-praktis.md) |
| **Susah hafal kode?** | [umum/03-tips-mengingat-kode.md](umum/03-tips-mengingat-kode.md) |
| **Kode error / tidak jalan** | [umum/04-troubleshooting-keamanan.md](umum/04-troubleshooting-keamanan.md) |

---

## ⚡ Navigasi Kilat — 10 Kode Paling Sering Dipakai

| Kebutuhan | Kode | Buka |
|---|---|---|
| Cek IMEI | `*#06#` | [umum/01-kode-ussd-mmi-universal.md](umum/01-kode-ussd-mmi-universal.md) |
| Cek panggilan dialihkan (sadap?) | `*#21#` → Panggil | [umum/01-kode-ussd-mmi-universal.md](umum/01-kode-ussd-mmi-universal.md) |
| Hapus semua alihan | `##002#` → Panggil | [umum/01-kode-ussd-mmi-universal.md](umum/01-kode-ussd-mmi-universal.md) |
| Cek call waiting | `*#43#` | [umum/01-kode-ussd-mmi-universal.md](umum/01-kode-ussd-mmi-universal.md) |
| Field Test iPhone | `*3001#12345#*` | [ios/02-field-test-mode.md](ios/02-field-test-mode.md) |
| Testing Android | `*#*#4636#*#*` | [android/03-diagnostik-system.md](android/03-diagnostik-system.md) |
| Test hardware Samsung | `*#0*#` | [android/07-kode-vendor.md](android/07-kode-vendor.md) |
| CIT Xiaomi | `*#*#6484#*#*` | [android/07-kode-vendor.md](android/07-kode-vendor.md) |
| ProjectMenu Huawei/HarmonyOS | `*#*#2846579#*#*` | [harmonyos/01-harmonyos-codes.md](harmonyos/01-harmonyos-codes.md) |
| Nokia soft reset | `*#7780#` (hati-hati!) | [feature-phone/01-feature-phone-codes.md](feature-phone/01-feature-phone-codes.md) |

---

## 🧠 Baru! Tips Menghafal

Semua kode dibuat gampang diingat via cerita & mnemonic — lihat [umum/03-tips-mengingat-kode.md](umum/03-tips-mengingat-kode.md).

## 📜 Lisensi

MIT / CC-BY 4.0 — bebas pakai, modifikasi, sebar ulang. Lihat [LICENSE](LICENSE) & [umum/05-referensi.md](umum/05-referensi.md).
