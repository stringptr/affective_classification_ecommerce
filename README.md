# Data Mining Kelompok 4 - Kelas A
<p align="center">
  Anindya Artanti Pambudi | L0224002<br>
  Prayuda Afifan Handoyo | L0224008<br>
  Satria Manggala Putra Pratama | L0224024<br> 
  Viola Herfina Putri | L0224026<br> 
</p>

# Affective Classification — E-commerce Reviews

Klasifikasi emosi (5 kelas: Happy, Love, Sadness, Fear, Anger) dan sentimen (Positive/Negative) pada ulasan e-commerce menggunakan 4 algoritma dengan GridSearchCV + 5-fold Stratified CV.

## Struktur

```
├── notebooks/
│   └── modelling.ipynb              # Main: preprocessing → 40 eksperimen → export model
├── data/
│   ├── raw/ecommerce_reviews.csv     # Dataset (5400 ulasan)
│   ├── intermediate/                 # Cache preprocessing
│   └── util/
├── model/
│   ├── sentiment/inference_v1.joblib
│   └── emotion/inference_v1.joblib
└── pyproject.toml
```

## Setup

```bash
uv sync
```
