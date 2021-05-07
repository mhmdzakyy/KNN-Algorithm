# KNN-Algorithm

mengklasifikasikan obyek baru berdasarkan atribut dan sample-sample dari training data. Algoritma k-NN menggunakan klasifikasi ketetanggaan sebagai nilai prediksi dari sampel uji yang baru.

Diberikan dataset (himpunan data) Pima India Diabetes Dataset (PIDD) pada file “Diabetes.csv”. Dataset tersebut berisi 768 objek data (baris). Buatlah lima datasets baru menggunakan skema 5-fold cross-validation. Pertama, bagi objek data ke dalam lima subsets (sub himpunan) dengan porsi yang sama, masing-masing berisi sat per lima (20%) data. Kemudian, buat lima dataset baru dengan komposisi objek-objek data pada training set (data latih) dan testing set (data uji) sebagai berikut:
* Baris ke-1 sampai baris ke-614 sebagai training set dan sisanya sebagai testing set;
* Baris ke-1 sampai baris ke-461 ditambah baris ke-642 sampai 768 sebagai training set dan yang lain sebagai testing set;
* Baris ke-1 sampai baris ke-307 ditambah baris ke-462 sampai 768 sebagai training set dan yang lain sebagai testing set;
* Baris ke-1 sampai baris ke-154 ditambah baris ke-308 sampai 768 sebagai training set dan yang lain sebagai testing set; dan
* Baris ke-155 sampai sampai 768 sebagai training set dan yang lain sebagai testing set.

## Hal yang Diobservasi
* Pemilihan ukuran jarak yang digunakan
* Teknik prapemrosesan data
* Teknik rekayasa fitur
* Strategi penggunaan algoritma kNN
* Pemilihan nilai k terbaik untuk proses seleksi dan estimasi model kNN

## Proses yang Dibangun
* Perhitungan ukuran jarak
* Prapemrosesan data
* Klasifikasi kNN
* Pemilihan nilai k terbaik
* Perhitungan rata-rata akurasi kNN menggunakan 5-fold cross-validation

## Output
* Nilai k terbaik hasil pembelajaran kNN; dan
* Rata-rata akurasi kNN menggunakan 5-fold cross-validation.
