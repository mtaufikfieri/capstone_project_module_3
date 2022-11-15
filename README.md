# Capstone Project Module 3 JCDSVL - California House Pricing

### Context

Dataset ini didasarkan pada data perumahan dari sensus di negara Amerika Serikat pada kota California di tahun 1990. Data ini bersisi lokasi, demography, dan informasi general terhadap rumah kota California.

### Business Problem

Setiap developer perumahan memiliki kesulitan untuk menentukan harga rumah dan juga lokasi untuk membangun rumah tersebut, agar terjadinya kesalahan pada letak rumah dan harga itu sendiri tidak akan salah.

Developer rumah tentu akan mencari lokasi yang bagus untuk membangun suatu perumahan. contoh; developer rumah tidak akan sembarangan membuat model perumahan jika tidak mengetahui atau memahami lokasi perumahan akan dibangun, pasti nya developer rumah akan ingin mengetahui perkiraan harga rumah, fasilitas, pendapatan dan lainnya terhadap lokasi perumahan yang akan di bangun. Dan hal-hal tersebut tentu berpengaruh terhadap penjualan dari rumah tersebut.

### Goals

Tujuan adalah kebutuhan penting, karena memungkinkan kita untuk mengidentifikasi cara mendekati masalah dan mengidentifikasi jenis sistem pembelajaran mesin yang dimilikinya. Tujuan di sini adalah untuk memprediksi harga rata-rata perumahan di distrik tersebut. Ini sangat penting karena mungkin menjadi faktor penentu apakah akan berinvestasi di lokasi atau tidak.

### Analytic Approach

Jadi, yang perlu kita lakukan adalah membuat analisa data untuk dapat menemukan pola dari fitur-fitur yang ada, yang membedakan satu properti dengan yang lainnya.

Selanjutnya, kita akan membangun suatu model regresi yang akan membantu perusahaan untuk dapat menyediakan 'tool' prediksi harga jual rumah yang baru, yang mana akan berguna untuk developer dalam menentukan lokasi serta harga rumah di suatu kawasan tertentu.

### Metric Evaluation

Evaluasi metrik yang akan digunakan adalah RMSE, MAE, dan MAPE, di mana RMSE adalah nilai rataan akar kuadrat dari error, MAE adalah rataan nilai absolut dari error, sedangkan MAPE adalah rataan persentase error yang dihasilkan oleh model regresi. Semakin kecil nilai RMSE, MAE, dan MAPE yang dihasilkan, berarti model semakin akurat dalam memprediksi harga sewa sesuai dengan limitasi fitur yang digunakan.

Selain itu, kita juga bisa menggunakan nilai R-squared atau adj. R-squared jika model yang nanti terpilih sebagai final model adalah model linear. Nilai R-squared digunakan untuk mengetahui seberapa baik model dapat merepresentasikan varians keseluruhan data. Semakin mendekati 1, maka semakin fit pula modelnya terhadap data observasi. Namun, metrik ini tidak valid untuk model non-linear.
