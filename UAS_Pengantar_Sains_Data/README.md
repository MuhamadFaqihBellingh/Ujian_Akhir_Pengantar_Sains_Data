# Ujian Akhir Pengantar Sains Data - Analisis Data Obesitas

Repositori ini berisi dataset yang digunakan dalam Ujian Akhir Pengantar Sains Data dan kode untuk melakukan analisis terhadap data tersebut.

## Struktur Folder:
- **data_soal_UAS_2024.2_Urgensi.xlsx**: Dataset yang digunakan dalam ujian (dalam format Excel).
- **analisis_data.py**: Script Python yang digunakan untuk menganalisis data.
- **Visualisasi**:Dokumentasi visual
- **README.md**: Dokumentasi repositori ini, yang menjelaskan cara menggunakan dataset dan menjalankan analisis di Google Colab.

## Cara Menjalankan Kode di Google Colab:

1. **Buka Notebook Colab**:
   - Anda bisa membuat notebook baru di [Google Colab](https://colab.research.google.com/).
   - Pilih **File > Open notebook**, kemudian pilih tab **GitHub**.
   - Masukkan URL repositori GitHub Saya:  
     `https://github.com/MuhamadFaqihBellingh/Ujian_Akhir_Pengantar_Sains_Data`  
     Setelah itu, pilih file notebook atau buat yang baru.

2. **Upload Dataset ke Colab**:
   - Setelah membuka notebook, pertama-tama upload file dataset **data_soal_UAS_2024.2_Urgensi.xlsx** ke Colab dengan menggunakan kode berikut:
   
   ```python
   from google.colab import files
   uploaded = files.upload()
