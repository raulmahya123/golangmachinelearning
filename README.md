# golangmachinelearning

Dataset Iris: Dataset ini terdiri dari 150 sampel bunga iris yang masing-masing diklasifikasikan menjadi 
tiga jenis yaitu setosa, versicolor, dan virginica. Variabel targetnya adalah
jenis bunga iris, sedangkan variabel fiturnya adalah panjang dan lebar kelopak dan mahkota bunga.


## Algoritma yang di pakai KNN
lgoritma K-Nearest Neighbors (KNN) adalah salah satu algoritma Machine Learning Supervised Learning yang digunakan untuk klasifikasi dan regresi. Algoritma KNN mencari sejumlah K tetangga terdekat dari suatu data baru dan menentukan kelas atau nilai target data baru berdasarkan mayoritas dari tetangga-tetangga tersebut.

Dalam proses KNN, langkah-langkah yang umum dilakukan adalah sebagai berikut:

Tentukan jumlah K tetangga terdekat yang akan dicari.

Hitung jarak antara data baru dengan setiap data yang ada pada dataset menggunakan suatu metrik jarak seperti Euclidean distance atau Manhattan distance.

Pilih K data dengan jarak terdekat dari data baru.

Tentukan kelas atau nilai target dari data baru berdasarkan mayoritas kelas atau nilai target dari K data terdekat.

Hasilkan prediksi untuk data baru.

Algoritma KNN cukup sederhana dan mudah diimplementasikan, namun performanya dapat dipengaruhi oleh jumlah data dan dimensi data pada dataset. Algoritma ini lebih cocok digunakan pada dataset dengan jumlah data sedang dan dimensi yang tidak terlalu banyak.

Selain itu, dalam proses KNN, pemilihan parameter K juga sangat penting. Jika K terlalu kecil, model akan menjadi lebih sensitif terhadap noise pada data, sedangkan jika K terlalu besar, model akan menjadi lebih cenderung mengabaikan perbedaan antara kelas-kelas pada data. Oleh karena itu, pemilihan nilai K yang tepat sangat penting dalam proses KNN.

## Cara Merunning
1.Git clone folder ini
2.go mod tidy
3.go run main.go
4.langsung muncul
