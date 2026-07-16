# ☁️ SaifulCloud Center

> Aplikasi Manajemen Cloud AWS (Amazon EC2 & Amazon S3) berbasis Python + Jupyter Notebook

---

## 🚀 Overview

**SaifulCloud Center** adalah aplikasi sederhana berbasis Python yang digunakan untuk mengelola layanan cloud AWS, khususnya:

- ⚡ Amazon EC2 (Compute)
- 🗂️ Amazon S3 (Storage)

Aplikasi ini dibuat menggunakan **Jupyter Notebook** dengan integrasi AWS SDK (Boto3), sehingga cocok untuk pembelajaran Cloud Computing.

---

## 🎯 Tujuan Project

Project ini bertujuan untuk:
- Memahami konsep dasar Cloud Computing
- Mengimplementasikan layanan AWS menggunakan Python
- Melakukan manajemen EC2 & S3 secara sederhana
- Membuat interface interaktif dengan Jupyter Notebook

---

## 🧰 Teknologi yang Digunakan

- 🐍 Python 3
- ☁️ AWS EC2
- 🗄️ AWS S3
- 📦 Boto3 (AWS SDK)
- 📓 Jupyter Notebook
- 🎛️ ipywidgets

---

## 📁 Struktur Project

SaifulCloud-Center/  
│  
├── .gitignore                  → Mengatur file yang tidak diupload ke GitHub  
├── SaifulCloud_Center.ipynb    → Notebook utama aplikasi  
├── requirements.txt            → Daftar library Python  
├── manual penggunaan.pdf       → Panduan penggunaan aplikasi  
├── EC2_Compute_Saiful_amri.png → Screenshot fitur EC2  
├── S3_Bucket_Saiful_amri.png   → Screenshot fitur S3  
└── README.md                   → Dokumentasi project  

---

### 📌 Penjelasan Struktur

- **.gitignore**  
  Mengabaikan file seperti cache, environment, dll agar tidak ikut terupload.

- **SaifulCloud_Center.ipynb**  
  File utama berisi kode program untuk mengelola AWS EC2 dan S3.

- **requirements.txt**  
  Berisi library yang harus diinstall seperti `boto3` dan `ipywidgets`.

- **manual penggunaan.pdf**  
  Panduan penggunaan aplikasi dalam bentuk PDF.

- **EC2_Compute_Saiful_amri.png**  
  Tampilan hasil fitur EC2.

- **S3_Bucket_Saiful_amri.png**  
  Tampilan hasil fitur S3.

- **README.md**  
  Dokumentasi utama project.

---

## ⚙️ Instalasi & Setup

### 1. Clone Repository
git clone https://github.com/username/saifulcloud-center.git  
cd saifulcloud-center  

### 2. Install Dependencies
pip install -r requirements.txt  

### 3. Konfigurasi AWS
aws configure  

Masukkan:
- AWS Access Key  
- AWS Secret Key  
- Region  
- Output format (json)  

---

## ▶️ Menjalankan Aplikasi

jupyter notebook  

Buka file:  
SaifulCloud_Center.ipynb  

Jalankan semua cell secara berurutan.

---

## ✨ Fitur Aplikasi

### ⚡ Amazon EC2 Management

Fitur ini digunakan untuk mengelola instance EC2:

- **Launch Instance**  
  Membuat instance EC2 baru di AWS

- **Stop Instance**  
  Menghentikan instance yang sedang berjalan

- **Terminate Instance**  
  Menghapus instance EC2 secara permanen

---

### 🗂️ Amazon S3 Management

Fitur ini digunakan untuk mengelola bucket S3:

- **Create Bucket**  
  Membuat bucket baru

- **List Bucket**  
  Menampilkan daftar bucket yang tersedia

- **Delete Bucket**  
  Menghapus bucket dari AWS

---

## 📘 Manual Penggunaan

### 🔹 Persiapan

Pastikan sudah menginstall:
- Python  
- Jupyter Notebook  
- Library dari requirements.txt  

Dan sudah melakukan konfigurasi AWS menggunakan:
aws configure  

---

### 🔹 Menjalankan Aplikasi

1. Buka terminal / CMD  
2. Masuk ke folder project  
3. Jalankan perintah:
   jupyter notebook  
4. Buka file:
   SaifulCloud_Center.ipynb  
5. Jalankan semua cell secara berurutan  

---

### 🔹 Cara Menggunakan EC2

1. Pilih menu EC2  
2. Klik **Launch Instance** untuk membuat instance baru  
3. Masukkan parameter instance (Instance ID, tipe, dll)  
4. Untuk menghentikan instance → klik **Stop Instance**  
5. Untuk menghapus instance → klik **Terminate Instance**

---

### 🔹 Cara Menggunakan S3

1. Pilih menu S3  
2. Masukkan nama bucket  
3. Klik **Create Bucket**  
4. Untuk melihat bucket → gunakan fitur list  
5. Untuk menghapus bucket → klik **Delete Bucket**

---

## 🖥️ Tampilan Aplikasi

### 🔹 EC2 Management
![EC2](EC2_Compute_Saiful_amri.png)

### 🔹 S3 Management
![S3](S3_Bucket_Saiful_amri.png)

---

## 🧪 Hasil Pengujian

✅ Launch EC2 Instance berhasil  
✅ Stop EC2 Instance berhasil  
✅ Terminate EC2 Instance berhasil  
✅ Create S3 Bucket berhasil  
✅ Delete S3 Bucket berhasil  

---

## 👤 Author

**Saiful Amri**  
📚 Mahasiswa Cloud Computing  
🏫 Universitas Islam Sultan Agung Semarang  

---

## 📄 License

Project ini dibuat untuk keperluan akademik & pembelajaran.

---

## ⭐ Support

Jika project ini membantu:
- ⭐ Star repository  
- 🍴 Fork project  
- 📢 Share ke teman  

---
