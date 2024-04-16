# Klasifikasi dan Regresi dengan Artificial Neural Network 
### Nama : Siti Nurrahmasita
### NPM  : 2108107010015

# Tentang Datasets:
## 1. Klasifikasi: 
https://www.kaggle.com/datasets/aparnashankar/facebook-ads-dataset
Dataset ini dapat digunakan dalam menganalisis kinerja kampanye iklan Facebook dengan menggunakan algoritma SVM untuk klasifikasi pengguna yang mengklik iklan berdasarkan waktu yang dihabiskan di situs dan gaji mereka.
Keseluruhan atribut yang ada di dalamnya:
  - Names: Nama pengguna (tidak digunakan dalam analisis)
  - Time Spent on Site: Waktu yang dihabiskan pengguna di situs (dalam satuan menit)
  - Salary: Gaji pengguna (dalam satuan dollar)
  - Clicked: Apakah pengguna mengklik iklan atau tidak (1=yes, 0=no)

## 2. Regresi:
https://www.kaggle.com/datasets/yasserh/student-marks-dataset
Dataset ini terdiri dari tiga kolom: `number_courses`, `time_study`, dan `Marks`. Berikut adalah penjelasan singkat tentang setiap kolom:
  - number_courses: Kolom ini mewakili jumlah kursus atau mata pelajaran yang diambil oleh seorang siswa dalam suatu periode tertentu. Jumlah kursus dapat menjadi indikator beban akademik atau tingkat komitmen siswa terhadap pendidikannya.
  - time_study: Kolom ini mengacu pada waktu yang dihabiskan oleh seorang siswa untuk belajar dalam satuan jam. Variabel ini dapat mencerminkan tingkat upaya atau dedikasi siswa terhadap pembelajaran.
  - Marks: Kolom ini mencerminkan nilai atau prestasi akademik yang diperoleh oleh siswa dalam kursus atau mata pelajaran yang diambilnya. Nilai ini dapat diberikan dalam sakala presentasi.
Dataset ini dapat digunakan untuk menganalisis hubungan antara jumlah kursus, waktu belajar, dan prestasi akademik siswa. Misalnya, Anda dapat menjelajahi apakah ada hubungan antara jumlah kursus yang diambil dan prestasi akademik, atau apakah ada pola yang dapat ditemukan dalam waktu belajar dan prestasi akademik siswa. Analisis semacam itu dapat memberikan wawasan yang berharga bagi pendidik dan pengambil keputusan pendidikan untuk meningkatkan kualitas pembelajaran dan hasil akademik siswa.

# Virtual Environment
  - Code ini dijalankan di windows dengan membuat Virtual Environment: python -m venv venv
  - Install requirements di bawah ini: pip install -r requirements.txt
  - Mengaktifkan Virtual Environment: venv\Scripts\activate
  - Optional: deactivate

# Hasil Klasifikasi dan Regresi
## 1. Klasifikasi
Akurasi Support Vector Machine : 0.864

Akurasi Artificial Neural Network : 0.85

Pada hasil klasifikasi di atas, terlihat bahwa model yang dibangun menggunakan algoritma Artificial Neural Network (ANN) memiliki tingkat akurasi yang sedikit lebih rendah dibandingkan dengan model yang menggunakan Support Vector Machine (SVM). Dengan demikian, untuk masalah klasifikasi yang sama, SVM mungkin lebih diunggulkan karena kemampuannya untuk menghasilkan prediksi yang lebih akurat.

## 2. Regresi
  - Akurasi Support Vector Machine :
    - Root Mean Squared Error (RMSE): 4.79727415341508
    - Mean Absolute Error (MAE): 3.875983538503933
    - R^2 Score (R^2): 0.8867359859912022
  - Akurasi Artificial Neural Network
    - Root Mean Square Error (RMSE): 4.013239946067064
    - Mean Absolute Error (MAE): 3.24169791507721
    - R-squared (R^2): 0.9076470291782653

Dalam perbandingan metrik evaluasi yang terdiri dari Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), dan R-squared (R^2), model ANN memiliki kinerja yang sedikit lebih baik daripada model SVM. Meskipun perbedaannya mungkin tidak signifikan, model ANN mampu menghasilkan prediksi dengan tingkat akurasi yang lebih tinggi, menunjukkan kemampuan yang lebih baik dalam memodelkan hubungan antara fitur dan target dalam dataset yang diberikan.
