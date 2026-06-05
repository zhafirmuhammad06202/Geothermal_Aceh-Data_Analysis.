# 🌋 Geospatial & Geochemical Analysis of Geothermal Potential in Aceh, Indonesia

> Exploratory Data Analysis (EDA) untuk memetakan dan mengevaluasi potensi energi panas bumi di wilayah Aceh menggunakan Python — mendukung kemandirian energi lokal.

---

## 🗺️ Live Demo

| Peta | Link |
|------|------|
| 🟢 Peta Geothermal Interaktif | [Buka Demo →](https://zhafirmuhammad06202.github.io/Geothermal_Aceh-Data_Analysis./peta_geothermal_aceh.html) |
| 🛰️ Peta Satelit Geothermal | [Buka Demo →](https://zhafirmuhammad06202.github.io/Geothermal_Aceh-Data_Analysis./peta_satelit_geothermal.html) |

---

## 📌 Project Overview

Aceh memiliki potensi panas bumi yang sangat besar namun belum dimanfaatkan secara optimal. Proyek ini menggunakan Python untuk menganalisis data geokimia dan geospasial dari 6 lokasi manifestasi panas bumi di Aceh, guna mengidentifikasi lokasi dengan risiko korosi rendah dan potensi reservoir terbaik.

**Lokasi yang dianalisis:** Seulawah Agam · Jaboi Sabang · Ie Seu-um · Pulo Aceh · Gayo Lues · Bener Meriah

---

## 🔍 Key Findings

| Lokasi | Suhu (°C) | pH | Silica (ppm) | Status |
|--------|-----------|-----|---------------|--------|
| Ie Seu-um | 85 | 7.5 | 80 | ✅ Optimal — risiko korosi rendah |
| Jaboi Sabang | 105 | 3.2 | 210 | ⚠️ pH asam tinggi |
| Seulawah Agam | 98 | 2.5 | 150 | ❌ Risiko korosi sangat tinggi |
| Gayo Lues | 92 | 6.8 | 120 | ✅ Potensi baik |
| Bener Meriah | 88 | 5.5 | 110 | 🔶 Perlu kajian lanjut |
| Pulo Aceh | 45 | 8.1 | 25 | 🔶 Suhu rendah |

> **Kesimpulan:** Ie Seu-um adalah lokasi paling strategis karena pH netral (7.5) meminimalisir biaya perawatan infrastruktur dibanding Seulawah Agam (pH 2.5).

---

## 🛠️ Tech Stack

| Library | Fungsi |
|---------|--------|
| Pandas | Data manipulation & analysis |
| NumPy | Numerical computation |
| Plotly Express | Interactive geochemical charts |
| Folium | Interactive geospatial mapping |

---

## 📊 Analysis Performed

- **Geospatial Mapping** — Memetakan titik manifestasi panas bumi ke peta satelit interaktif dengan color coding berdasarkan temperatur
- **Geochemical Correlation** — Analisis hubungan Silica (ppm) vs temperatur permukaan untuk estimasi kualitas reservoir
- **Technical Risk Assessment** — Evaluasi pH di setiap lokasi untuk menentukan risiko korosi infrastruktur
- **Comparative Study** — Analisis kondisi vegetasi dan aksesibilitas wilayah via Satellite Imagery

---

## 📁 Repository Structure

Geothermal_Aceh-Data_Analysis/
├── Geothermal_Aceh.ipynb          # Main analysis notebook
├── peta_geothermal_aceh.html      # Interactive geothermal map
├── peta_satelit_geothermal.html   # Interactive satellite map
└── README.md

---

## 🚀 How to Run

```bash
git clone https://github.com/zhafirmuhammad06202/Geothermal_Aceh-Data_Analysis..git
pip install pandas numpy plotly folium
jupyter notebook Geothermal_Aceh.ipynb
```

---

## 👤 Author

**Muhammad Zhafir Ar-Radhi**
Geophysics Graduate — Universitas Syiah Kuala, Banda Aceh, Indonesia

[![Upwork](https://img.shields.io/badge/Upwork-Available-brightgreen?style=flat&logo=upwork)](https://www.upwork.com/freelancers/~01b7ee8f43bc40e8fc)
[![GitHub](https://img.shields.io/badge/GitHub-zhafirmuhammad06202-black?style=flat&logo=github)](https://github.com/zhafirmuhammad06202)

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.
