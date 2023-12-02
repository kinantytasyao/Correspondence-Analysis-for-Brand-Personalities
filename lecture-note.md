**Summary day 1**

* *Correspondence Analysis* adalah metode unsupervised learning yang digunakan untuk teknik data analysis dalam memetakan hubungan variabel kategorikal.
* *Brand personality* adalah karakteristik sifat manusia yang melekat pada suatu brand
* *Tabel kontingensi* atau cross-tabulation adalah tabel yang berisi nilai frekuensi/kemunculan suatu kategori data.
* Input dari Correspondence Analysis adalah sebuah tabel kontingensi, sehingga biasanya perlu dilakukan data preprocessing untuk menghasilkan tabel kontingensi.


**Summary day 2**

*Ballon plot*

* Balloon plot digunakan untuk membuat tabel grafis dimana setiap sel menampilkan lingkaran berwarna yang ukurannya mencerminkan besar nilainya.

*Mosaic plot*

* Mosaic plot digunakan untuk memvisualisasikan tabel kontingensi dan untuk memeriksa hubungan antara variabel kategori
* Mosaic plot dapat diinterpresaikan sebagai berikut:
  + Sebuah sel diarsir biru jika kita yakin bahwa sel tersebut lebih tinggi dari sel lain dalam baris yang sama
  + Sebuah sel diarsir dengan warna merah jika kita yakin bahwa sel tersebut lebih rendah dari sel lain pada baris yang sama
  
*Uji Chi-Square*

* uji chi-square adalah sebuah uji statistik untuk menentukan apakah ada hubungan yang signifikan antara dua variabel kategorik
* Uji hipotesis untuk Chi-Square Test adalah sebagai berikut.
  + $H_0$ : Variabel baris dan kolom dari tabel kontingensi adalah independen
  + $H_1$ : Variabel baris dan kolom adalah dependen (memiliki hubungan yang signifikan)
* H0 akan ditolak jika pvalue yang dihasilkan `chisq.test()` < 0.05