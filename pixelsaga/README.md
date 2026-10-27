<div align="center">

# 🗺️ PIXEL SAGA: WIRA GEOGRAFI

**RPG Idle Pixel-Art untuk Belajar Geografi KSSM Tingkatan 2 & 3**

*Belajar sambil bermain — jawab soalan DSKP, kalahkan raksasa, buru senjata UNIQUE!*

![Version](https://img.shields.io/badge/versi-2.0-amber)
![Platform](https://img.shields.io/badge/platform-Web%20(Hitam%20Retro)-blue)
![Bahasa](https://img.shields.io/badge/bahasa-Bahasa%20Malaysia-green)
![Kurikulum](https://img.shields.io/badge/kurikulum-KSSM%20%7C%20DSKP%20KPM-red)

**[🎮 MAIN SEKARANG](https://encikashraf.github.io/geografi/)**

</div>

---

## 📖 Tentang Permainan Ini

**Pixel Saga: Wira Geografi** ialah permainan RPG idle berasaskan web yang menggabungkan **sistem pertempuran pixel-art** dengan **bank soalan Geografi KSSM** yang komprehensif. Murid menjawab soalan untuk menyerang raksasa, mengumpul Gold & Berlian, membeli kelengkapan, dan mengalahkan BOSS — semuanya sambil mengulang kaji silibus Geografi Tingkatan 2 dan 3 mengikut DSKP KPM.

> 🎯 **Konsep:** *"Belajar tanpa rasa belajar"* — gamifikasi penuh yang menjadikan ulang kaji Geografi menyeronokkan.

---

## ✨ Ciri-Ciri Utama

### ⚔️ Pertempuran Idle 60 FPS
- Watak **menyerang secara automatik** — gaya idle RPG sebenar
- **8 jenis raksasa** unik: Goblin Skala, Roh Peta, Imp Ribut, Golem Batuan, Naga Monsun, Bandit Gurun, Penyangak Arang, Warden Hutan
- **4 BOSS epik** setiap gelombang ke-5: Maharaja Golem Tektonik, Naga Ais Tundra Purba, Dewa Ribut Siklon, Titan Pemanasan Global
- Kesan **screen shake** semasa serangan kritikal & kemahiran

### 📚 Bank Soalan DSKP (420 Soalan)
| Aras | Bilangan | Ganjaran Betul | Penalti Salah |
|------|----------|---------------|---------------|
| 🟢 Mudah | 139 | +30 Gold, +10 Pt | -15 Gold |
| 🔵 Sederhana | 139 | +65 Gold, +25 Pt | -35 Gold |
| 🔴 Tinggi | 118 | +130 Gold, +50 Pt + **Drop UNIQUE!** | -70 Gold |
| ⚡ Event Krisis | 24 | +15–35 Berlian, +180 Gold | Tiada |

- Merangkumi **11 bab Tingkatan 2** dan **12 bab Tingkatan 3** (silibus penuh DSKP)
- Setiap soalan disertakan **huraian pembelajaran**

### 🎒 Sistem Kelengkapan RPG Lengkap
- **7 slot**: Helmet, Senjata, Baju, Seluar, Kasut, Cincin, Rantai
- Watak bermula **kosong (0/7)** — beli menggunakan Gold di Kedai
- 4 tahap kelangkaan: **Biasa → Jarang → Epik → UNIQUE**
- Senjata khusus kelas: **Kesatria Tektonik (Melee)** & **Pemanah Kompas (Ranger)**

### 💎 Ekonomi & Ganjaran
- **Gold** — jawab soalan & kalahkan raksasa
- **Berlian** — selesaikan **Event Krisis Random** (muncul setiap 50–90 saat)
- **Pasar Berlian** — tebus Peti UNIQUE, Pakej Gold, atau Berkat Kekal
- **Meter Buruan UNIQUE** — 3 jawapan betul Aras Tinggi berturut = **jaminan drop UNIQUE!**

### 🎨 Grafik & Audio
- **Pixel art 2D** direka khas — setiap watak & raksasa ada identiti visual sendiri
- **Latar parallax 7 lapisan** dengan awan, burung, gunung & pokok beranimasi
- **4 biome** berbeza: Hutan Tropika, Banjaran Titiwangsa, Pesisir Bakau, Bandar
- **SFX chiptune** dijana secara langsung (Web Audio API) — 9 jenis bunyi, tanpa fail audio luar
- Kesan partikel, damage text terapung & vignette sinematik

---

## 🎮 Cara Main

1. **Cipta watak** — masukkan nama, pilih Tingkatan (2/3/Gabungan) dan kelas
2. **Jawab soalan** — pilih aras kesukaran di panel kiri, jawab untuk menyerang
3. **Kumpul harta** — Gold untuk beli kelengkapan, Berlian dari Event Krisis
4. **Naik level** — kalahkan raksasa & boss untuk EXP
5. **Buru UNIQUE** — jawab soalan Aras Tinggi untuk peluang kelengkapan legenda!

| Kelas | Kelebihan |
|-------|-----------|
| ⚔️ **Kesatria Tektonik** (Melee) | +25% HP & DEF, penalti Gold -20%, kemahiran **Hentakan Tektonik** (AoE) |
| 🏹 **Pemanah Kompas** (Ranger) | +20% Kritikal, laju serang 1.5×, +20% Gold & Point, kemahiran **Hujan Panah Monsun** |

---

## 🚀 Jalankan Secara Tempatan

Tiada pemasangan diperlukan:

```bash
# Pilihan 1: Buka terus
# Klik dua kali fail index.html

# Pilihan 2: Guna server tempatan (disyorkan)
python -m http.server 8000
# atau
npx serve
```

Kemudian buka `http://localhost:8000` dalam pelayar.

> ⚠️ **Nota:** Perlu sambungan internet untuk memuatkan Tailwind CSS, FontAwesome & Google Fonts (CDN). Kemajuan permainan disimpan secara automatik dalam pelayar (localStorage).

---

## 🛠️ Teknologi

| Teknologi | Kegunaan |
|-----------|----------|
| HTML5 Canvas | Enjin render permainan 60 FPS |
| Vanilla JavaScript | Logik permainan (tanpa framework) |
| Web Audio API | SFX chiptune dijana secara programatik |
| Tailwind CSS | Antara muka UI |
| FontAwesome | Ikon |
| localStorage | Simpanan kemajuan automatik |

---

## 📋 Penjajaran Kurikulum

Bank soalan dibina berdasarkan **Dokumen Standard Kurikulum dan Pentaksiran (DSKP)** Geografi KSSM yang dikeluarkan oleh **Kementerian Pendidikan Malaysia (KPM)**:

**Tingkatan 2:** Skala & Jarak • Peta Topografi • Pergerakan Bumi • Cuaca & Iklim Malaysia • Pengangkutan • Telekomunikasi • Iklim Asia • Pengangkutan Asia • Pemanasan Global • Teknologi Hijau • Kerja Lapangan

**Tingkatan 3:** Jadual & Graf • Carta Pai • Persekitaran Fizikal & Biodiversiti • Tumbuh-tumbuhan Malaysia • Hidupan Liar Malaysia • Sumber Semula Jadi • Kegiatan Ekonomi • Tumbuh-tumbuhan Dunia • Kerjasama Ekonomi Dunia • Sumber Hutan • Kitar Semula • Kerja Lapangan

---

## 📄 Lesen

Dibangunkan untuk kegunaan pendidikan. Sila gunakan dengan bijak untuk pembelajaran Geografi.

---

<div align="center">

**Dibina dengan ❤️ untuk murid-murid Geografi Malaysia**

*Pixel Saga: Wira Geografi © 2025 · Encik Ashraf*

</div>
