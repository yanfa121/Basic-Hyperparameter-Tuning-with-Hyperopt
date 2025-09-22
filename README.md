# Hyperopt - Hyperparameter Optimization
## 📌 Apa itu Hyperopt?


## Hyperopt
Hyperopt adalah library Python untuk optimasi hyperparameter secara otomatis menggunakan algoritma probabilistik seperti Random Search dan Tree of Parzen Estimators (TPE).


## ⚡ Konsep Utama

Search Space → ruang nilai hyperparameter (diskrit, kontinyu, log-uniform, dsb).

Objective Function → fungsi yang ingin diminimalkan/maksimalkan (mis. error/loss).

Optimization Algorithm → metode pencarian (TPE, Random).

Trials → menyimpan hasil setiap percobaan.


## 🛠 Cara Kerja

Tentukan ruang pencarian (hp.choice, hp.uniform, dll).

Definisikan fungsi objective (validasi akurasi/loss).

Jalankan optimasi dengan fmin() dan algoritma (tpe.suggest, rand.suggest).

Ambil hasil hyperparameter terbaik.


## ✅ Kelebihan

Efisien dibanding grid search/random search biasa.

Mendukung model ML & DL (Scikit-learn, XGBoost, PyTorch, TensorFlow).

Bisa paralel untuk mempercepat pencarian.


## ⚠️ Kekurangan

Dokumentasi resmi relatif singkat.

Visualisasi terbatas dibanding Optuna.


## Contact
- Yanfa Anandika
- Email : yanfaanandika21@gmail.com
- LinkedIn : [Yanfa Anandika](https://www.linkedin.com/in/yanfa-anandika-a663bb170/)
- GitHub : [yanfa121](https://github.com/yanfa121)
