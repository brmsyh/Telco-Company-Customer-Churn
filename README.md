# Telco Customer Churn Analysis

## Repository Outline
1. **README.md**                       - Penjelasan gambaran umum project
2. **Notebook.ipynb**   - Notebook Python berisi data cleaning dan analisis statistik


## Problem Background
Perusahaan telekomunikasi mengalami tingkat churn (berhentinya pelanggan) yang cukup tinggi, terutama di segmen pelanggan kontrak bulanan. Ketidakpahaman terhadap karakteristik pelanggan yang churn menyebabkan sulitnya menyusun strategi retensi yang efektif. Oleh karena itu, analisis ini dilakukan untuk memahami pola dan faktor utama penyebab churn berdasarkan data historis pelanggan.

## Project Output
Output dari project ini berupa:
- Analisis statistik deskriptif dan inferensial untuk memahami perilaku pelanggan churn
- Visualisasi dashboard interaktif di Tableau Public
- Rekomendasi strategis berbasis data untuk mengurangi churn

## Data
- Dataset: https://www.kaggle.com/datasets/blastchar/telco-customer-churn
- Ukuran: 7.043 baris & 21 kolom
- Fitur utama: Churn, Contract, MonthlyCharges, TotalCharges, Tenure, InternetService
- Handling: Nilai kosong pada TotalCharges dihapus setelah dikonversi ke tipe numerik

## Method
Metode utama yang digunakan dalam project ini meliputi:
- Statistik Deskriptif: analisis rata-rata, median, sebaran, outlier
- Statistik Inferensial: uji Chi-Square untuk melihat hubungan antara churn dan jenis kontrak
- Visualisasi Data: bar plot, boxplot, line chart, dll

## Stacks
Bahasa Pemrograman: 
- `Python 3.10`
Libraries:
- `pandas`, `numpy`: untuk manipulasi data
- `matplotlib`, `seaborn`: untuk visualisasi statistik

Tools:
- Tableau Public (dashboard interaktif)
- Jupyter Notebook`

## Reference
- [Dataset]('https://www.kaggle.com/datasets/blastchar/telco-customer-churn')
- [Tableau Public Dashboard]('https://public.tableau.com/app/profile/yunido.baheramsyah/viz/CustomerChurnAnalysis_17502595278150/DataVisualization?publish=yes')
---