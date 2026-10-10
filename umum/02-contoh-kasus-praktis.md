# Umum — Contoh Kasus Praktis (Semua HP)

> Skenario nyata — Android, iPhone, HarmonyOS, Feature Phone.

---

## 1. Beli HP Bekas — Checklist 5 Menit (Semua HP)

### Android

1. `*#06#` → samakan IMEI layar vs dusbook vs bodi.
2. Samsung `*#0*#` / Xiaomi `*#*#6484#*#*` → tes RGB, touch (usap semua kotak), speaker, proximity, getar. Detail: [android/04-tes-hardware.md](../android/04-tes-hardware.md) & [android/07-kode-vendor.md](../android/07-kode-vendor.md)
3. Xiaomi `*#*#6485#*#*` → `MF_02` (cycle), `MB_06` (health).
4. `*#*#4636#*#*` → cek dBm & tes data.

### iPhone

1. `*#06#` → IMEI vs **Settings → General → About**.
2. `*3001#12345#*` → cek RSRP/SINR & band. → [ios/02-field-test-mode.md](../ios/02-field-test-mode.md)
3. **Settings → Battery → Battery Health** → Maximum Capacity & Cycle Count. → [ios/04-tips-ios.md](../ios/04-tips-ios.md)
4. **Settings → General → About → Carrier Lock** = No SIM restrictions.

### Huawei HarmonyOS

`*#*#2846579#*#*` → ProjectMenu → Battery / Network / Veneer Info. → [harmonyos/01-harmonyos-codes.md](../harmonyos/01-harmonyos-codes.md)

### Nokia / Feature Phone

` *#06#` → IMEI; `*#0000#` → firmware & model; `*#7370#` jangan dicoba (hard reset!). → [feature-phone/01-feature-phone-codes.md](../feature-phone/01-feature-phone-codes.md)

---

## 2. Sinyal Lemah / Mau Kunci 4G/5G

| HP | Cara |
|---|---|
| **Android** | `*#*#4636#*#*` → Phone Info 1/2 → Set Preferred Network Type → `LTE Only` / `NR Only`. Detail: [android/05-jaringan-seluler.md](../android/05-jaringan-seluler.md) |
| **iPhone** | Tidak bisa lock band via kode — Field Test read-only (`*3001#12345#*`). Solusi: pindah lokasi / Reset Network Settings / hubungi operator. |
| **HarmonyOS** | `*#*#2846579#*#*` → Network Information Query (read-only band). |
| **Feature Phone** | Settings → Network selection → manual/auto. |

> `LTE Only` di Android tanpa VoLTE → tidak bisa telpon biasa. Aktifkan VoLTE dulu (Xiaomi: `*#*#86583#*#*`).

---

## 3. Curiga Panggilan Dialihkan / Disadap (Semua HP — butuh Panggil)

> Jalan di Android, iPhone, HarmonyOS, Feature Phone — karena diproses operator.

1. Ketik `*#21#` → **tap Panggil**. Lihat `Voice: Forwarded to +62...` ?
2. Jika nomor asing bukan voicemail operator → ketik `##002#` → **Panggil** → `Erasing successful`.
3. Verifikasi ulang `*#21#` → Panggil → harusnya `Not Forwarded`.

Detail lengkap: [01-kode-ussd-mmi-universal.md](01-kode-ussd-mmi-universal.md)

---

## 4. IMEI untuk Bea Cukai / Kemenperin (Semua HP)

` *#06#` → Panggil (iOS/feature phone) / auto (Android) — catat IMEI 1/2, cek di situs Kemenperin / bea cukai. **Jangan sebar IMEI di medsos.** Lebih lanjut: [03-troubleshooting-keamanan.md](03-troubleshooting-keamanan.md)

[← 01 Universal](01-kode-ussd-mmi-universal.md) | [→ 03 Tips Menghafal](03-tips-mengingat-kode.md)
