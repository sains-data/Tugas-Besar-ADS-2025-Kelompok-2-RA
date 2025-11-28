# Tugas-Besar-ADS-2025-Kelompok-2-RA

## Nama Anggota Kelompok:
1. Ni Made Okta Viola Darma Putri | 124450005
2. Mufti Maulana | 124450011
3. Jacinda Keysha Alvara | 124450023
4. Hafidz Wahdiansyah |124450064

### Cara Menjalankan Script
1. Download dataset pada , DATASET.csv
2. Download code R pada file code codeR_2_RA.Rmd
3. Buka script tersebut menggunakan R studio 
4. Instal packed yang dibutuhkan ("readx1" , "ggplot2" , "dplyr")
5. pada bagian import data : mhs <- read.csv("C:/Users/Hype G12/Downloads/DATASET.csv"), jangan lupa untuk mengganti path sesuai direktori masing
6. Jalankan Script dengan cara tekan tombol Run

### Paket R yang digunakan :
library(readx1), library(ggplot2), library(dplyr)

### Penjelasan Singkat Dataset
Penerima beasiswa di kampus itera sering kali menjadi tanda tanya bagi sebagian orang tentang bagaimana sebenarnya kondisi ekonomi mahasiswa penerima beasiswa dan juga apakah mahasiswa penerima beasiswa benar-benar memiliki kemampuan akademik ataupun non akademik yang jauh diatas rata-rata mahasiswa non-beasiswa. Eksplorasi ini akan menghasilkan beberapa informasi profil mahasiswa Itera penerima beasiswa secara general. Fokus utama eksplorasi profil tersebut adalah variabel-variabel yang sering dijadikan tolak ukur dalam seleksi beasiswa.

### Struktur Repository
1. DATASET.csv - File dataset utama
2. README.md - File petunjuk dengan penjelasan R packages dan dataset
3. codeR_2_RA.Rmd - Script R dalam format R Markdown
4. Poster_2_RA.png - File poster hasil analisis

### Variabel:
'IPK Terakhir :', 'Apakah Penerima Beasiswa :', 'Keterlibatan Organisasi', 'Jenis Pekerjaan Ayah:', 'Jenis Pekerjaan Ibu :', dan 'Pendapatan Orangtua'.

### Metode:
Eksplorasi Data Kategorik, Selang Kepercayaan, Uji Mann Withney (non parametrik) dan Uji Normalitas (Shapiro Wilk test).


