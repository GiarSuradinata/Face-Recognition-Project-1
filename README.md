# Face-Recognition-Project-1
Pembelajaran pengenalan wajah pada Computer Vision

## 📌 Latar Belakang

Face Recognition merupakan salah satu aplikasi penting dalam bidang Computer Vision, yang digunakan pada berbagai sistem seperti:
- sistem keamanan
- absensi berbasis wajah
- verifikasi identitas
- human–computer interaction

Dalam project ini, dilakukan pendekatan **deep learning berbasis Convolutional Neural Network (CNN)** untuk mengenali wajah menggunakan arsitektur **GoogLeNet (Inception Network)**.

---

## 🎯 Tujuan Project

Tujuan dari project ini adalah:
1. Membangun sistem **face recognition berbasis CNN**
2. Melatih model menggunakan arsitektur **GoogLeNet**
3. Mengevaluasi performa model dalam mengenali wajah berdasarkan kelas/identitas

---

## 🗂 Dataset

- Dataset berisi **gambar wajah**
- Setiap gambar diklasifikasikan ke dalam **kelas identitas tertentu**
- Dataset dibagi menjadi:
  - Data training
  - Data validation
  - (Opsional) Data testing

### Preprocessing Data
Tahapan preprocessing meliputi:
- Resize gambar ke ukuran input model
- Normalisasi pixel
- Konversi label ke format numerik
- Data augmentation (jika digunakan)

---

## 🧠 Arsitektur Model

### GoogLeNet (Inception Network)

GoogLeNet merupakan CNN yang menggunakan **Inception Module**, yang memungkinkan:
- ekstraksi fitur multi-skala
- efisiensi parameter
- performa tinggi pada tugas klasifikasi visual

Model ini digunakan sebagai **classifier wajah**, di mana setiap wajah dipetakan ke kelas identitas tertentu.

---

## ⚙️ Konfigurasi Training

- Framework: **PyTorch**
- Model: **GoogLeNet**
- Loss Function: Cross Entropy Loss
- Optimizer: Adam / SGD
- Epoch: sesuai eksperimen pada notebook
- Batch size: disesuaikan dengan kapasitas GPU
- Hardware: GPU (jika tersedia)
