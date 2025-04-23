# Dewi-Pitri-Yani_Autoencoder_Deep-Learning

# Dataset:
- Struktur folder: Dataset/train/{color, grayscale}.
  
  Dataset/
    train/
        color/      (Berisi gambar berwarna)
        grayscale/  (Berisi gambar grayscale yang sesuai)
  
- Ukuran: 20 gambar (18 training, 2 validasi), ukuran 256x256.
- Diproses: diubah ukuran, dinormalisasi.

# Arsitektur:
- Autoencoder konvolusional dengan encoder (Conv2D + MaxPooling) dan decoder (Conv2D + UpSampling).
- Aktivasi: ReLU (lapisan tersembunyi), Sigmoid (lapisan output).

# Performa:
- Training selesai, tapi loss stagnan. Indikasi kurangnya data atau masalah pada model.
- Hasil visual: Gambar berwarna kurang baik.

# Kesimpulan:
Kode dasar autoencoder sudah berfungsi, tetapi perlu data lebih banyak, loss lebih lanjut, penyesuaian arsitektur atau parameter lain agar hasilnya lebih baik. 
