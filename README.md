Klasifikasi menggunakan Jaringan Saraf Tiruan
Deskripsi Proyek
Proyek ini bertujuan untuk mengimplementasikan model klasifikasi menggunakan jaringan saraf tiruan untuk dataset Fashion MNIST. Dataset ini terdiri dari gambar-gambar berukuran 28x28 piksel yang mewakili 10 kategori pakaian yang berbeda.

Langkah-langkah Proyek
1. Persiapan
Import Library: Mengimpor TensorFlow untuk membangun dan melatih model, NumPy untuk manipulasi data, dan Matplotlib untuk visualisasi.
2. Dataset
Fashion MNIST: Dataset ini terdiri dari 60,000 gambar pelatihan dan 10,000 gambar uji, diambil dari berbagai produk pakaian.
3. Preprocessing Data
Normalisasi: Nilai piksel dalam gambar dinormalisasi ke rentang [0, 1] dengan membagi setiap nilai piksel dengan 255.
4. Membangun Arsitektur Model
Arsitektur: Model jaringan saraf terdiri dari:
Flatten Layer sebagai input untuk meratakan gambar 2D menjadi array 1D.
Dense Layers dengan aktivasi ReLU sebagai lapisan tersembunyi.
Dense Layer dengan aktivasi softmax sebagai output untuk menghasilkan probabilitas dari setiap kategori pakaian.
5. Pelatihan Model
Compiling: Menggunakan fungsi loss 'sparse_categorical_crossentropy', optimizer 'adam', dan metrik 'accuracy'.
Early Stopping: Menggunakan EarlyStopping untuk menghentikan pelatihan jika tidak terjadi peningkatan dalam loss pada data validasi.
6. Evaluasi Model
Pengukuran Kinerja: Mengukur akurasi model pada data uji yang tidak terlibat dalam pelatihan.
7. Prediksi
Prediksi: Menggunakan model untuk memprediksi kategori pakaian dari gambar-gambar baru pada data uji.
Hasil dan Kesimpulan
Model yang dihasilkan mencapai akurasi sekitar [nilai akurasi di sini] pada data uji.
Kesimpulan: Proyek ini menunjukkan bahwa jaringan saraf tiruan dapat efektif digunakan untuk melakukan klasifikasi gambar dalam konteks dataset Fashion MNIST.
