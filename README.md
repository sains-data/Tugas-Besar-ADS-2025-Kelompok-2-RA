# Tugas-Besar-ADS-2025-Kelompok-2-RA

## Nama Anggota Kelompok:
1. Ni Made Oktaviola Dharma Putri | 124450005
2. Mufti Maulana | 124450011
3. Jacinda Keysha Alvara | 124450023
4. Hafidz Wahdiansyah |124450064

Penerima beasiswa di kampus itera sering kali menjadi tanda tanya bagi sebagian orang tentang bagaimana sebenarnya kondisi ekonomi mahasiswa penerima beasiswa dan juga apakah mahasiswa penerima beasiswa benar-benar memiliki kemampuan akademik ataupun non akademik yang jauh diatas rata-rata mahasiswa non-beasiswa. Eksplorasi ini akan menghasilkan beberapa informasi profil mahasiswa Itera penerima beasiswa secara general. Fokus utama eksplorasi profil tersebut adalah variabel-variabel yang sering dijadikan tolak ukur dalam seleksi beasiswa.

### Variabel:
'IPK Terakhir :', 'Apakah Penerima Beasiswa :', 'Keterlibatan Organisasi', 'Jenis Pekerjaan Ayah:', 'Jenis Pekerjaan Ibu :', dan 'Pendapatan Orangtua'.

### Metode:
Eksplorasi Data Kategorik, Selang Kepercayaan, Uji Mann Withney (non parametrik) dan Uji Normalitas (Shapiro Wilk test).

### Paket R yang digunakan :
library(readx1), library(ggplot2), library(dplyr)

### Penjelasan Singkat Dataset
Dataset yang digunakan bersumber dari Survei Karakteristik Mahasiswa ITERA (N = 458), yang memuat berbagai informasi dasar mahasiswa seperti jenis kelamin, prodi, tahun angkatan, IPK, daerah asal, status tempat tinggal, jumlah saudara, total anggota keluarga, serta nominal uang saku dari orang tua. Pada penelitian ini, fokus analisis diarahkan pada dua variabel utama: Jumlah Anggota Keluarga (X) sebagai variabel independen dan Uang Saku (Y) yang sebelumnya berbentuk kategori kemudian diubah menjadi data numerik sebagai variabel dependen. Kedua variabel tersebut dianalisis menggunakan statistik deskriptif, korelasi Pearson, dan regresi linear sederhana.

