# 🫀 DTW Heartbeat Analysis Dashboard

Dashboard analisis **Dynamic Time Warping (DTW)** pada dataset suara detak jantung ([Heartbeat Sounds — Kaggle](https://www.kaggle.com/datasets/kinguistics/heartbeat-sounds)).

> Institut Teknologi Sepuluh Nopember (ITS) — Surabaya

---

## 🔗 Live Demo

👉 **[Buka Dashboard](https://<username>.github.io/dtw-heartbeat-dashboard)**

---

## 📋 Isi Dashboard

| Bagian | Keterangan |
|---|---|
| Dataset overview | Statistik ringkas 585 file audio, 5 kelas |
| Kelas interaktif | Klik tiap kelas untuk melihat waveform & deskripsi |
| Cara kerja DTW | Visualisasi 3 langkah algoritma + heatmap cost matrix |
| Hasil analisis | 4 chart: distribusi, jarak DTW, intra/inter class, akurasi |

## 🛠 Teknologi

- HTML5 + CSS3 + Vanilla JS
- Chart.js 4.4 — untuk visualisasi data
- Google Fonts — IBM Plex Mono + Inter

## 📁 Struktur

```
dtw-heartbeat-dashboard/
└── index.html    ← satu file, siap deploy
```

## 🚀 Cara Deploy ke GitHub Pages

1. Buat repo baru di GitHub (misal: `dtw-heartbeat-dashboard`)
2. Upload `index.html` ke repo
3. Buka **Settings → Pages → Source: main branch → / (root)**
4. Klik **Save** — dashboard live dalam ~1 menit

## 📊 Dataset

- **Sumber:** [kinguistics/heartbeat-sounds](https://www.kaggle.com/datasets/kinguistics/heartbeat-sounds)
- **Referensi:** Bentley, P. et al. (2011). *Classifying Heart Sounds Challenge*

## 📓 Notebook

Analisis lengkap tersedia di `DTW_Heartbeat_ITS.ipynb` (Google Colab).
