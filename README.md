# Klasifikasi Fashion MNIST menggunakan Jaringan Saraf Tiruan

Proyek ini bertujuan untuk mengimplementasikan model klasifikasi menggunakan jaringan saraf tiruan untuk dataset Fashion MNIST. Dataset ini terdiri dari gambar berukuran 28x28 piksel yang mewakili 10 kategori pakaian yang berbeda.

### Dataset

Proyek ini menggunakan dataset Fashion MNIST yang terdiri dari 60,000 gambar pelatihan dan 10,000 gambar uji. Setiap gambar direpresentasikan dalam skala abu-abu 28x28 piksel.

### Langkah-langkah Proyek:

1. **Persiapan Data**: 
   - Memuat dataset dan membaginya menjadi data pelatihan dan data uji.
   - Melakukan normalisasi data dengan membagi nilai piksel dengan 255.

2. **Membangun Model**: 
   - Menggunakan arsitektur jaringan saraf dengan lapisan-lapisan Dense dan aktivasi ReLU.
   - Melatih model dengan data pelatihan dan memvalidasi dengan data validasi untuk menghindari overfitting.

3. **Pelatihan dan Evaluasi**: 
   - Mengompilasi model dengan fungsi loss 'sparse_categorical_crossentropy', optimizer 'adam', dan metrik 'accuracy'.
   - Menggunakan Early Stopping untuk menghentikan pelatihan jika tidak ada peningkatan pada data validasi.
   - Mengevaluasi model pada data uji untuk mengukur akurasi dan performa secara keseluruhan.

4. **Visualisasi**: 
   - Menampilkan grafik untuk memvisualisasikan akurasi dan loss pada setiap epoch selama pelatihan.

### Persyaratan:

Untuk menjalankan proyek ini, pastikan Anda memiliki:
- Python 3.x
- Libraries: TensorFlow, NumPy, Matplotlib

### Penggunaan:

Untuk menggunakan proyek ini:
1. Pastikan semua persyaratan terpenuhi dengan menginstal libraries yang diperlukan.
2. Eksekusi script pada file Python yang disediakan (`main.ipynb`) untuk melihat detail implementasi dan hasilnya.

