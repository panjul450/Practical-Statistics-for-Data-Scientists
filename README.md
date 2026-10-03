# Ringkasan Praktik Statistik untuk Data Science

Repositori ini memuat kumpulan kode program Python beserta materi dari buku *Practical Statistics for Data Scientists: 50+ Essential Concepts Using R and Python* (Edisi ke-2) karya Peter Bruce, Andrew Bruce, dan Peter Gedeck.

## Daftar Pustaka & Sumber
- **Buku Referensi**: Bruce, P., Bruce, A., & Gedeck, P. (2020). *Practical Statistics for Data Scientists* (2nd ed.). O'Reilly Media.
- **Repositori Asli**: [GitHub - gedeck/practical-statistics-for-data-scientists](https://github.com/gedeck/practical-statistics-for-data-scientists)

---

## Ringkasan Per Bab

### Bab 1: Eksplorasi dan Analisis Data (EDA)
Fokus pada teknik investigasi awal guna mengenali profil dan karakteristik data secara mendalam:
- **Ukuran Pemusatan:** Mempelajari mean, median, trimmed mean, serta mean/median berbobot, sekaligus memahami pentingnya penggunaan statistik yang tahan (*robust*) terhadap data pencilan.
- **Ukuran Variabilitas:** Menghitung tingkat penyebaran data melalui varians, standar deviasi, MAD, IQR, hingga persentil.
- **Visualisasi Distribusi:** Menyajikan sebaran data menggunakan sarana visual seperti boxplot, histogram, density plot (KDE), dan diagram batang untuk data kategorikal.
- **Analisis Hubungan Antarvariabel:** Meneliti keterkaitan data lewat koefisien korelasi Pearson, scatterplot, hexbin plot, contour plot, tabel kontingensi, hingga violin plot.

### Bab 2: Data dan Distribusi Sampling
Membahas mekanisme penarikan sampel serta teori probabilitas yang mendasarinya:
- **Konsep Sampling & CLT:** Memahami dasar-dasar penarikan sampel, risiko bias, pembentukan distribusi sampling, serta cara mengukur galat menggunakan *Standard Error* (SE) dan *Central Limit Theorem* (CLT).
- **Metode Bootstrap:** Menaksir parameter statistik dan membangun interval kepercayaan (*confidence interval*) melalui teknik resampling berulang.
- **Variasi Distribusi Probabilitas:** Mengenali karakteristik berbagai bentuk distribusi teoretis, seperti Normal (dilengkapi z-score dan QQ-plot), *long-tailed*, t-Student, Binomial, Chi-Square, F, Poisson, Eksponensial, hingga Weibull.

### Bab 3: Pengujian Signifikansi dan Eksperimen Statistik
Menyoroti tata cara perancangan eksperimen serta kaidah pengujian hipotesis:
- **A/B Testing & Resampling:** Memahami alur A/B testing, perumusan hipotesis nol (H0) dan alternatif (H1), serta pengujian berbasis metode resampling (*permutation test*).
- **Evaluasi Hipotesis:** Cara membaca p-value, menentukan ambang batas signifikansi (alpha), serta menghindari jebakan Kesalahan Tipe 1 dan Tipe 2.
- **Uji Statistik Klasik:** Menggunakan pendekatan analitis seperti uji-t, ANOVA (uji-F), uji chi-square (independensi dan *goodness-of-fit*), serta Fisher's exact test.
- **Manajemen Eksperimen:** Mengatasi kendala pengujian berganda (*multiple testing* / p-hacking) serta menghitung kebutuhan ukuran sampel dan *power* statistik sebelum uji coba dimulai.

### Bab 4: Prediksi dan Analisis Regresi
Mengkaji teknik pemodelan untuk menghubungkan variabel prediktor dengan target kontinu:
- **Regresi Linier:** Membahas regresi sederhana dan berganda berbasis metode *least squares*, nilai prediksi (*fitted values*), residual, serta cara menginterpretasikan koefisiennya.
- **Evaluasi & Seleksi Model:** Menilai performa model menggunakan RMSE, R-squared, statistik-t, kriteria AIC, serta pemilihan fitur secara *stepwise*.
- **Kendalikan Bias & Hubungan Variabel:** Mengelola variabel kategorikal (*dummy coding*), mengatasi multikolinearitas, memperhitungkan variabel pengganggu (*confounder*), dan menganalisis efek interaksi.
- **Diagnostik & Model Non-linier:** Memeriksa residual untuk mendeteksi pencilan, titik pengaruh tinggi (seperti *leverage* dan Cook's distance), varians tidak konstan (heteroskedastisitas), serta memperluas model non-linier dengan pendekatan polinomial, *spline*, dan GAM.