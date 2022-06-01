Nama  : Dicky Ahmad Fadhilah
NPM   : 16119892
Kelas : 3KA18

Penjelasan dari UTS Pengantar Sains Data yang telah dikerjakan :
pada Ujian yang dikerjakan ini dilakukan sebuah prediksi saham dengan menggunakan RBF model, Linear model, Polinomial model pada SVR (Support Vector Regression) dengan hasil sebagai berikut :
![image](https://user-images.githubusercontent.com/105706888/171325169-8412d26b-c2cb-4f3a-afe1-99c959047cba.png)
dari hasil yang telah didapat pada gambar di atas dapat disimpulkan bahwa RBF Model lah yang paling baik untuk menentukan prediksi pada tanggal 29 September 2021, dikarenakan terdapat titik-titik yang bersinggungan dengan garis hijau(RBF Model) yang mana titik-titik tersebut merupakan original data atau nilai ADJ_CLOSE_PRICE dari tiap tanggal.

Jawaban dari soal PDF 

4. Dari hasil yang telah didapat pada gambar di atas, dapat disimpulkan bahwa RBF Model lah yang paling baik untuk menentukan prediksi pada tanggal 29 September 2021, dikarenakan terdapat titik-titik yang bersinggungan dengan garis hijau(RBF Model) yang mana titik-titik tersebut merupakan original data atau nilai ADJ_CLOSE_PRICE dari tiap tanggal.

5. Pada run ke 1 : memberikan deskripsi di komentar tentang apa yang dilakukan kode tersebut.

Pada run ke 2 : Melakukan impor paket /libraries untuk memudahkan penulisan program.

Pada run ke 3 : Selanjutnya memuat data saham Google (GOOG) yang dapatkan dari finance.yahoo.com ke dalam sebuah variabel bernama 'df' kependekan dari data frame.

Pada run ke 4 : mencetak baris data terakhir, Harga Penutupan Penyesuaian

Pada run ke 5 : Membuat kembali bingkai data dengan mendapatkan semua data kecuali baris terakhir yang akan digunakan untuk menguji model nantinya, dan simpan data baru dengan baris terakhir hilang kembali ke 'df'.

Pada run ke 6 : Membuat variabel yang akan digunakan sebagai kumpulan data independen dan dependen dengan menyetelnya sama dengan daftar kosong.

Pada run ke 7 : Dapatkan semua baris dari kolom Tanggal simpan ke dalam variabel yang disebut 'df_days' dan dapatkan semua baris dari kolom Adj Close Price dan simpan datanya ke dalam variabel.

Pada run ke 8 : Buat kumpulan data independen 'X' dan simpan data dalam variabel 'days'. Buat kumpulan data dependent 'y' dan simpan data tersebut dalam variabel 'adj_close_prices'. Keduanya dapat dilakukan dengan menambahkan data ke masing-masing daftar.

Pada run ke 9 : mencetak dan melihat hari apa yang dicatat dalam kumpulan data.

Pada run ke 10 : membuat dan mencoba 3 model Support Vector Regression (SVR) yang berbeda dengan tiga kernel yang berbeda untuk melihat mana yang berkinerja paling baik.
