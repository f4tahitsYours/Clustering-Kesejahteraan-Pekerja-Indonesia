# Clustering Kesejahteraan Pekerja Indonesia

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0.2-orange)
![Pandas](https://img.shields.io/badge/Pandas-1.4.0-red)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5.1-green)

Proyek ini bertujuan untuk menganalisis dan mengelompokkan tingkat kesejahteraan pekerja di Indonesia menggunakan teknik clustering. Dataset yang digunakan mencakup berbagai indikator ekonomi seperti garis kemiskinan, upah minimum, pengeluaran, dan rata-rata upah di berbagai provinsi Indonesia.

## 📋 Dataset

Proyek ini menggunakan 4 dataset utama yang digabungkan:

1. `garisKemiskinan.csv` - Data garis kemiskinan per provinsi
2. `minUpah.csv` - Data upah minimum provinsi (UMP)
3. `pengeluaran.csv` - Data pengeluaran rumah tangga
4. `rataRataUpah.csv` - Data rata-rata upah pekerja

## 🛠️ Teknologi yang Digunakan

- Python 3.8+
- Libraries:
  - Pandas untuk manipulasi data
  - Scikit-learn untuk algoritma clustering (KMeans)
  - Matplotlib dan Seaborn untuk visualisasi
  - PCA dan t-SNE untuk reduksi dimensi

## 📊 Hasil Analisis

### Cluster yang Ditemukan

Analisis clustering menghasilkan 4 kelompok utama:

1. **Cluster 0**: Masyarakat perdesaan dengan pengeluaran dominan makanan
2. **Cluster 1**: Masyarakat perkotaan dengan pengeluaran dominan non-makanan
3. **Cluster 2**: Masyarakat perdesaan dengan pengeluaran dominan non-makanan
4. **Cluster 3**: Masyarakat perkotaan dengan pengeluaran dominan makanan

### Metrik Evaluasi

- Silhouette Score: 0.6891 (baik)
- Jumlah cluster optimal: 4 (berdasarkan elbow method)

## 📂 Struktur File

```
clustering-kesejahteraan-pekerja-indonesia/
├── data/
│   ├── garisKemiskinan.csv
│   ├── minUpah.csv
│   ├── pengeluaran.csv
│   ├── rataRataUpah.csv
│   └── Dataset_clustering.csv (hasil penggabungan)
├── clustering_analysis.ipynb (analisis utama)
│  
├── results/
│   └── Dataset_inisiasi.csv (hasil akhir dengan label cluster)
└── README.md
```

## 🚀 Cara Menjalankan

1. Clone repositori ini
   ```bash
   git clone https://github.com/username/clustering-kesejahteraan-pekerja-indonesia.git
   cd clustering-kesejahteraan-pekerja-indonesia
   ```

2. Buat environment virtual (opsional)
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate  # Windows
   ```

3. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

4. Jalankan notebook Jupyter
   ```bash
   jupyter notebook
   ```

## 📝 Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

## ✉️ Kontak

Untuk pertanyaan atau kolaborasi, silakan hubungi:

[Sultan Fatahillah] - [adjikp76@gmail.com]
