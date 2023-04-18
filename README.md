# Penarikan Kesimpulan dan Pengujian Hipotesis

## **Overview**
Tugas ini mengaplikasikan  konsep-konsep probabilitas dan statistika untuk menyelesaikan persoalan berikut.
- persoalan distribusi peluang variabel random
- persoalan menarik kesimpulan mengenai parameter populasi dari data hasil eksperimen
- persoalan pengujian hipotesis

## **Dataset Description**
Dataset yang diberikan adalah sebuah data `anggur.csv`. Dataset `anggur.csv` merupakan data metrik kualitas wine (minuman anggur) yang
mengandung 12 kolom sebagai berikut:
1. fixed acidity
2. volatile acidity
3. citric acid
4. residual sugar
5. chlorides
6. free sulfur dioxide
7. total sulfur dioxide
8. density
9. pH
10. sulphates
11. alcohol
12. quality

Catatan: Kolom 1-11 adalah kolom atribut (non-target), sedangkan kolom 12 adalah kolom
target. 

## **Problem Description**
Permasalahan pada tugas ini adalah melakukan analisis-analisis statistika berikut.
1. Menulis deskripsi statistika (Descriptive Statistics) dari semua kolom pada data yang bersifat numerik, terdiri dari mean, median, modus, standar deviasi, variansi, range, nilai minimum, maksimum, kuartil, IQR, skewness dan kurtosis. Boleh juga ditambahkan deskripsi lain.

2. Membuat Visualisasi plot distribusi, dalam bentuk histogram dan boxplot untuk setiap
kolom numerik. Berikan uraian penjelasan kondisi setiap kolom berdasarkan kedua plot
tersebut.

3. Menentukan setiap kolom numerik berdistribusi normal atau tidak. Gunakan normality test yang dikaitkan dengan histogram plot.

4. Melakukan test hipotesis 1 sampel,
<br> a. Nilai rata-rata pH di atas 3.29?
<br> b. Nilai rata-rata Residual Sugar tidak sama dengan 2.50?
<br> c. Nilai rata-rata 150 baris pertama kolom sulphates bukan 0.65?
<br> d. Nilai rata-rata total sulfur dioxide di bawah 35?
<br> e. Proporsi nilai total Sulfat Dioxide yang lebih dari 40, adalah tidak sama dengan 50% ? 

5. Melakukan test hipotesis 2 sampel,
<br> a. Data kolom fixed acidity dibagi 2 sama rata: bagian awal dan bagian akhir kolom. Benarkah rata-rata kedua bagian tersebut sama?
<br> b. Data kolom chlorides dibagi 2 sama rata: bagian awal dan bagian akhir kolom. Benarkah rata-rata bagian awal lebih besar daripada bagian akhir sebesar 0.001?
<br> c. Benarkah rata-rata sampel 25 baris pertama kolom Volatile Acidity sama dengan rata-rata 25 baris pertama kolom Sulphates ?
<br> d. Bagian awal kolom residual sugar memiliki variansi yang sama dengan bagian akhirnya?
<br> e. Proporsi nilai setengah bagian awal alcohol yang lebih dari 7, adalah lebih besar daripada, proporsi nilai yang sama di setengah bagian akhir alcohol?

## **Summary**
Pengerjaan permasalahan di atas diselesaikan dengan menggunakan beberapa library `Python` (`pandas`, `matplotlib`, `scipy`, `seaborn`, `statsmodels`). Kode pengerjaan dapat dilihat pada file `*.ipynb` yang terdapat pada folder `/src/`. Dokumen hasil pengerjaan dapat dilihat pada folder `/doc/`.

## **Authors**
| NIM | Nama |
| --- | ---- |
| 13521064 | Bill Clinton |
| 13521074 | Eugene Yap Jin Quan |



