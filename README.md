# Dicoding Collection Dashboard ✨

Dashboard ini adalah aplikasi interaktif yang dibuat dengan Streamlit untuk menganalisis data e-commerce, dengan fokus pada pengaruh keterlambatan pengiriman terhadap rating pelanggan restoran.

## Fitur Utama
- **Interaktif:** Pengguna dapat memfilter data berdasarkan tahun dan memilih jenis visualisasi yang diinginkan.
- **Visualisasi Lengkap:** Menyediakan boxplot, barplot, histogram, dan heatmap untuk mendukung insight analisis.
- **Analisis Mendalam:** Menggabungkan visualisasi dengan analisis statistik untuk memberikan gambaran lengkap dampak keterlambatan pengiriman terhadap kepuasan pelanggan.

---

## Setup Environment (VSCode & Python)

### Persyaratan
- **Python 3.9** atau versi lebih baru harus sudah terinstal.
- **Visual Studio Code (VSCode)** untuk kemudahan pengembangan dan debugging.

### Langkah-langkah
1. **Buka Terminal di VSCode:**  
   Pastikan kamu membuka terminal di VSCode di direktori proyek.

2. **Buat Virtual Environment:**  
   Jalankan perintah berikut untuk membuat virtual environment:
   ```bash
   python -m venv venv
Aktifkan Virtual Environment:

Pada Windows:
bash
Salin
Edit
.\venv\Scripts\activate
Pada macOS/Linux:
bash
Salin
Edit
source venv/bin/activate
Instal Dependencies:
Pastikan file requirements.txt sudah berada di direktori proyek dengan isi berikut:

ini
Salin
Edit
pandas==1.5.3
numpy==1.23.5
matplotlib==3.6.2
seaborn==0.12.2
streamlit==1.16.0
Kemudian, instal paket-paket tersebut dengan perintah:

bash
Salin
Edit
pip install -r requirements.txt
Menjalankan Aplikasi
Untuk menjalankan dashboard interaktif, jalankan perintah berikut di terminal (pastikan virtual environment telah aktif):

bash
Salin
Edit
streamlit run dashboard.py
Setelah perintah ini dijalankan, Streamlit akan membuka browser secara otomatis dan menampilkan dashboard interaktif.

Catatan
Pastikan file dashboard.py dan requirements.txt berada di direktori proyek.
Jika terdapat masalah dengan instalasi atau environment, periksa kembali apakah virtual environment sudah aktif dengan benar.
Buka proyek di VSCode untuk memudahkan modifikasi dan debugging.
