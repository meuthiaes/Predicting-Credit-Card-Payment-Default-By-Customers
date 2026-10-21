# Predicting Credit Card Payment Default

## Ringkasan Proyek
Proyek ini bertujuan untuk membangun model *machine learning* prediktif guna mengidentifikasi risiko keterlambatan pembayaran kartu kredit pada nasabah FinanKu. Dengan mendeteksi potensi gagal bayar secara lebih dini, pihak manajemen dapat menentukan langkah penanganan serta strategi mitigasi risiko bisnis yang lebih efektif dan proaktif.

## Target & Kriteria Keberhasilan
* **Accuracy & Recall:** > 60%
* **Pencapaian:** Model mampu mendeteksi sekurang-kurangnya 60% dari total pelanggan yang berpotensi mengalami keterlambatan pembayaran.

## Temuan Utama & Rekomendasi
* **Fitur Penting:** Perubahan saldo (*Delta Balance*), rata-rata saldo (*Mean Balance*), tingkat keaktifan (*Active Months*), dan durasi kepemilikan kartu (*Vintage Credit Card*) menjadi indikator utama risiko gagal bayar.
* **Rekomendasi Bisnis:** Mengelompokkan nasabah *High-Risk Unpaid* untuk mendapatkan penawaran restrukturisasi, penyesuaian limit kredit, atau pengiriman *reminder* otomatis sebelum jatuh tempo.

---
*Tech Stack: Python, Pandas, NumPy, Scikit-Learn, XGBoost, Matplotlib/Seaborn*
