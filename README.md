# Bike Sharing Dashboard

Dashboard ini dibuat menggunakan Streamlit untuk menganalisis data penyewaan sepeda berdasarkan berbagai faktor seperti cuaca, musim, dan waktu.

## Cara Menjalankan

1. **Persyaratan**
   Pastikan Anda telah menginstal Python dan pustaka yang diperlukan. Jika belum, Anda dapat menginstalnya dengan menjalankan perintah berikut:
   
   ```sh
   pip install pandas matplotlib seaborn streamlit
   ```

2. **Persiapkan Dataset**
   Pastikan file `day_clean.csv` dan `hour_clean.csv` tersedia di direktori yang sama dengan skrip Python.

3. **Menjalankan Dashboard**
   Jalankan perintah berikut di terminal atau command prompt:
   
   ```sh
   streamlit run Dashboard.py
   ```

4. **Akses Dashboard**
   Setelah menjalankan perintah di atas, dashboard akan terbuka secara otomatis di browser. Jika tidak, buka secara manual dengan mengakses URL yang muncul di terminal (biasanya `http://localhost:8501`).

## Fitur Dashboard
- **Tren Penyewaan Sepeda**: Menampilkan grafik jumlah penyewa sepeda waktu ke waktu.
- **Analisis Berdasarkan Pengguna**: Perbandingan pengguna terdaftar dan pengguna kasual.
- **Analisis Berdasarkan Cuaca dan Musim**: Melihat bagaimana faktor eksternal mempengaruhi jumlah penyewa.
- **Tren Penyewaan Berdasarkan Jam**: Menampilkan grafik penggunaan sepeda berdasarkan jam di sepanjang hari.

## Catatan
- Pastikan semua dependensi telah terinstal sebelum menjalankan dashboard.
- Jika terjadi error pada data, periksa apakah file CSV memiliki format yang sesuai.

---

Selamat menggunakan Bike Sharing Dashboard!
