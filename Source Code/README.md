
# Tugas Akhir Berita COVID-19

Berikut merupakan tahapan pembuatan sistem informasi Berita COVID-19

## 1. Persiapan data
##### a. Import semua file mysql pada folder Database TA
##### b. Untuk mendapatkan Data COVID-19 terbaru jalankan semua program python pada folder Data COVID-19 
##### c. Untuk mendapatkan Data Berita terbaru jalankan semua program pada folder Data Berita dengan command
    scrapy crawl covid-19 <nama file spider>
##### d. Untuk mendapatkan atribut tempat provinsi dan kota jalankan file tugas_akhir_add_tempat.ipynb pada folder Data Berita

## 2. Klasifikasi Teks
file sampel data berita berada di folder Klasifikasi Teks/Feature Engineering/Pickles_title/df.pickle

#### A. Pemrosesan Teks dan Rekayasa Fitur
    /Feature Engineering/Feature Engineering Title.ipynb
#### B. Model Training
- Jalankan Model Random Forest
```    
/Model Training/MT - Random Forest.ipynb
```
- Jalankan Model SVM
```    
/Model Training/MT - SVM.ipynb
```
- Jalankan Model KNN
```    
/Model Training/MT - KNN.ipynb
```
- Jalankan Model MNB
```    
/Model Training/MT - MultinomialNB.ipynb
```
- Perbandingan akurasi pada setiap model
```    
/Model Training/Best Model Selection.ipynb
```
- Memberikan Label pada Data Berita
```
/Prediksi Label/tugas_akhir_prediksi label.ipynb
```
## 3. Implementasi Web
    cd /Implementasi Web/TAHistoryCovid && php artisan serve