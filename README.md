# Dicoding Collection Dashboard ✨

Dashboard ini adalah aplikasi interaktif yang dibuat dengan Streamlit untuk menganalisis data e-commerce, dengan fokus pada pengaruh keterlambatan pengiriman terhadap rating pelanggan restoran.

## Fitur Utama
- **Interaktif**: Pengguna dapat memfilter data berdasarkan tahun dan memilih jenis visualisasi yang diinginkan.
- **Visualisasi Lengkap**: Menyediakan boxplot, barplot, histogram, dan heatmap untuk mendukung insight analisis.
- **Analisis Mendalam**: Menggabungkan visualisasi dengan analisis statistik untuk memberikan gambaran lengkap dampak keterlambatan pengiriman terhadap kepuasan pelanggan.

## Setup Environment (VSCode & Python)
### Persyaratan
- Python 3.9 atau versi lebih baru
- Visual Studio Code (VSCode)

### Langkah-langkah
1. Buka terminal di VSCode pada direktori proyek.
2. Buat virtual environment:
   ```sh
   python -m venv venv
   ```
3. Aktifkan virtual environment:
   - **Windows**:
     ```sh
     .\venv\Scripts\activate
     ```
   - **macOS/Linux**:
     ```sh
     source venv/bin/activate
     ```
4. Instal dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Menjalankan Aplikasi
Jalankan perintah berikut:
```sh
streamlit run dashboard.py
```

## Catatan
- Pastikan file `dashboard.py` dan `requirements.txt` ada di direktori proyek.
- Pastikan virtual environment telah aktif sebelum menjalankan aplikasi.

Selamat mencoba dan semoga dashboard ini bermanfaat untuk analisis data e-commerce kamu! 🚀
