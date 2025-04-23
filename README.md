# Dewi-Pitri-Yani_Autoencoder_Deep-Learning

# Dataset:
- Struktur folder: Dataset/train/{color, grayscale}.
  
  Dataset/
    train/
        color/      (Berisi gambar berwarna),
        grayscale/  (Berisi gambar grayscale yang sesuai)
  
- Ukuran: 20 gambar (18 training, 2 validasi), ukuran 256x256.
- Diproses: diubah ukuran, dinormalisasi.

# Arsitektur:
- Autoencoder konvolusional dengan encoder (Conv2D + MaxPooling) dan decoder (Conv2D + UpSampling).
- Aktivasi: ReLU (lapisan tersembunyi), Sigmoid (lapisan output).

# Performa:
- Training selesai, tapi loss stagnan. Indikasi kurangnya data atau masalah pada model.
- Hasil visual: Gambar berwarna kurang baik.

# Contoh Hasil Input dan Output Citra:
Fungsi show_results(model, X_val_gray, X_val_color, n=5) digunakan untuk menampilkan contoh hasil. Kode menampilkan 3 baris gambar:
- Gambar grayscale asli (input).
- Gambar yang diwarnai oleh model (prediksi).
- Gambar berwarna asli (ground truth).

# Kesimpulan:
Kode dasar autoencoder sudah berfungsi, tetapi perlu data lebih banyak, loss lebih lanjut, penyesuaian arsitektur atau parameter lain agar hasilnya lebih baik. 
