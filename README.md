# posttest-alprog-kelompok1C
# Anggota Kelompok:
# Jonathan Yuan Kendro (21060125130062)
# Geraldy Raihan Nurfauzan (2106012514032)
# Fitto Timothyus (21060125140152)
# Wisnu Arga Kusumaadmaja (21060125140165)
# M Fadly Restu Bundana (2106012514069)
# PEMBAGIAN TUGAS POSTEST:
# 1. Pembuatan grafik : Fitto Timothyus dan wisnu Arga Kusumaadmaja
# 2. Pembuatan kode : Jonathan Yuan Kendro
# 3. Pembuatan infografis dabn PPT : Muahmmad Fadly Restu Bundana dan Geraldy Raihan Nurfauzan
# 4. Pembuatan penilidan : Semua anggota kelompok

## Deskripsi Grafik

File `Grafik_Gabungan.ipynb` berisi gabungan analisis dari Grafik 1 sampai Grafik 5 dalam satu notebook. Notebook ini dibagi menjadi empat kategori utama:

### Kategori A (Agregasi)
Kategori A menghitung rata-rata harga rumah (`price`) berdasarkan `furnishingstatus`. Hasil perhitungan ditampilkan dengan Bar Chart sehingga perbedaan rata-rata harga antara rumah furnished, semi-furnished, dan unfurnished dapat dibandingkan dengan mudah.

### Kategori B (Tren/Filter)
Kategori B memfilter data rumah yang berada di jalan utama (`mainroad = "yes"`) dan memiliki AC (`airconditioning = "yes"`). Setelah data difilter, program menghitung rata-rata harga rumah dari kelompok tersebut dan menampilkannya dalam Bar Chart.

### Kategori C (Korelasi)
Kategori C menganalisis hubungan antara luas tanah (`area`) dan harga jual rumah (`price`). Nilai korelasi dihitung untuk melihat kekuatan hubungan kedua variabel, lalu Scatter Plot digunakan untuk memperlihatkan pola persebaran data.

### Kategori D (Distribusi)
Kategori D mengidentifikasi pencilan atau outlier pada data harga rumah (`price`) menggunakan metode IQR. Boxplot digunakan untuk menampilkan distribusi harga rumah sekaligus menunjukkan titik data yang termasuk pencilan.

