# Sentiment-Analysis-pada-Ulasan-Apps-Google-Play-berbasis-BERT
Penelitian ini menggunakan model BERT dari indoNLU Banchmark
Untuk mempelajari model BERT yang digunakan bisa mengunjungi Website indoNLU
https://www.indobenchmark.com/

BERT model yang digunakan pada penelitian ini dapat dilihat secara detail pada link berikut
https://huggingface.co/indobenchmark/indobert-base-p1

Penelitian ini menggunakan Dataset hasil scraping secara mandiri pada ulusan Google Play dengan bahasa Indonesia dengan jumlah data 3963 kalimat.
Dataset dibagi menjadi 3 data yaitu, data train, data test dan data valid, dengan rasio 60% : 20% : 20%.

## Detail Device yang digunakan :
1.	Processor Intel Core i5-5200U, 2.20GHz – 2.19GHz
2.	RAM 8 GB
3.	GPU Nvidia GeForce 840M
4.	Hardisk 1 TB
5.	SSD 120 GB

## Tentang indoNLU 
IndoNLU adalah sebuah koleksi sumber untuk riset dalam topik Natural Language Understanding (NLU) untuk Bahasa Indonesia dengan 12 aplikasi. Kami menyediakan kode untuk mereproduksi hasil dan model besar yang sudah dilatih sebelumnya (IndoBERT and IndoBERT-lite) yang dilatih dengan kumpulan tulisan berisi sekitar 4 miliar kata (Indo4B) dan lebih dari 20 GB dalam ukuran data teks. Proyek ini awalnya dimulai dari kerjasama antara universitas dan industri, seperti Institut Teknologi Bandung, Universitas Multimedia Nusantara, The Hong Kong University of Science and Technology, Universitas Indonesia, Gojek, dan Prosa.AI.

IndoNLU telah diterima oleh AACL-IJCNLP 2020 dan Anda dapat menemukan detailnya di paper kami https://www.aclweb.org/anthology/2020.aacl-main.85.pdf.

## Kesimpulan :
Pada penelitian ini telah dilakukan prediksi tugas sentimen analisis dengan menggunakan dataset ulasan aplikasi dari Google Play berbahasa 
Indonesia dengan menggunakan BERT yang menghasilkan akurasi sebesar 86%. Hasil akurasi dapat berubah-ubah tergantung tahapan preprocessing data 
dan juga proses pelabelan dataset yang digunakan. Tingkat akurasi terendah BERT pada penelitian ini berada pada angka 82%.
Ada kekurangan pada penelitian ini, melihat dari hasil grafik trainingterlihat bahwa masih terjadi overfitting dari model BERT yang digunakan, 
terlihat pada grafik train loss dan valid loss, nilai valid loss tidak sejalan dengan train loss yang menurun tetapi nilai valid loss nya meningkat.

