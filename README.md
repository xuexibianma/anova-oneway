# One-Way ANOVA Analysis

## 📌 Deskripsi
Repository ini berisi dataset dan Jupyter Notebook untuk melakukan **One-Way ANOVA** guna menganalisis pengaruh **metode pembelajaran** terhadap nilai ujian siswa.

## 📂 File dalam Repository
- `dataset/nilai.csv` → Dataset nilai ujian berdasarkan metode pembelajaran.
- `uji_anova.ipynb` → Notebook Jupyter untuk melakukan analisis One-Way ANOVA.

## 🚀 Cara Penggunaan
1. Unduh **dataset/nilai.csv** dan **uji_anova.ipynb**.
2. Buka **Jupyter Notebook** dan jalankan file `uji_anova.ipynb` secara bertahap.
3. Notebook akan melakukan:
   - Eksplorasi data.
   - Visualisasi distribusi nilai berdasarkan metode pembelajaran.
   - Melakukan **One-Way ANOVA** untuk melihat pengaruh metode belajar terhadap nilai ujian.

## 📊 Hipotesis Uji One-Way ANOVA
1. **Hipotesis Nol (H₀)**: Tidak ada perbedaan rata-rata nilai ujian antar metode pembelajaran.
2. **Hipotesis Alternatif (H₁)**: Setidaknya satu metode pembelajaran memiliki pengaruh signifikan terhadap nilai ujian.

## 📊 Interpretasi Hasil
- Jika **p-value** dari metode pembelajaran < 0.05 → metode pembelajaran memiliki pengaruh signifikan terhadap nilai ujian (Tolak H₀).
- Jika **p-value** dari metode pembelajaran ≥ 0.05 → metode pembelajaran tidak memiliki pengaruh signifikan terhadap nilai ujian (Gagal Tolak H₀).

💡 **Gunakan hasil ini untuk memahami apakah metode pembelajaran tertentu lebih efektif dibandingkan yang lain.**

---
📧 Jika ada pertanyaan atau ingin mengembangkan lebih lanjut, silakan diskusikan!
