# Building-Movies-Recommendation-System

## Bussiness Understanding
Sistem rekomendasi memprediksi peringkat atau preferensi pengguna untuk item tertentu. 
Ini dilakukan dengan menganalisis perilaku pengguna di masa lalu atau perilaku pengguna lain, sehingga rekomendasi didasarkan pada
data preferensi atau tingkah laku pengguna dari waktu ke waktu.

Secara umum, terdapat dua tipe rekomendasi yang umum digunakan, yaitu rekomendasi pada beranda dan rekomendasi untuk produk yang berkaitan.

Rekomendasi beranda merupakan jenis rekomendasi yang sering kita jumpai dalam kehidupan sehari-hari. Contoh umum dari rekomendasi ini bisa kita lihat di beranda aplikasi seperti Google Play Store, yang menampilkan aplikasi yang mungkin menarik bagi Anda. 
Hal yang sama juga berlaku untuk layanan streaming seperti Netflix, HBO Max, Disney+ dll, yang menyarankan film-film yang mungkin ingin Anda tonton saat Anda membuka beranda.

Sementara itu, rekomendasi produk yang disesuaikan dengan preferensi pengguna kerap dijumpai di platform e-commerce. 
Sebagai contoh, ketika Anda menggunakan Shopee atau Tokopedia untuk mencari suatu barang, akan ditampilkan produk-produk lain yang 
berhubungan dengan item yang sedang atau pernah Anda telusuri.

## Bussiness Problem
Masalah yang muncul adalah ketika user merasa tidak ada film yang cocok untuk ditonton yang muncul pada beranda 
karena tidak ada movies rekomendasi sistem yang diterapkan pada aplikasi,
sehingga menghilangkan minat menonton dari user yang berpotensi user untuk melakukan churn pada platfrom.

## Preparation
**Data Source**
[MovieLens 100K Dataset](https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset)

## Setup Environment - Anaconda

1. Clone Repository
   ```bash
   git clone https://github.com/RozyRangkuti/Building-Movies-Recommendation-System.git
   ```

2. Buka Terminal Anaconda, jalankan perintah berikut untuk membuat environment baru
   ```bash
   conda create --name myenv python=3.11
   ```
   
3. Aktifkan virtual environment dengan menjalankan perintah berikut ini
   ```bash
   conda activate myenv
   ```
   
4. Install semua requirements di dalam file "requirements.txt"
   ```bash
   pip install -r requirements.txt
   ```
