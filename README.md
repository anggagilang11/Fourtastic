# Job Description Classification
##  Project Overview
Ford, sebuah perusahaan teknologi berbasis CRM, menghadapi kesulitan dalam proses rekrutmen karena deskripsi pekerjaan yang terlalu panjang. Proyek ini bertujuan untuk membuat model machine learning yang dapat mengklasifikasikan kalimat dalam deskripsi pekerjaan ke dalam beberapa kategori, seperti Requirements, Education, Skill, Softskill, Responsibility, atau Experience. Dengan model ini, Ford dapat menyederhanakan deskripsi pekerjaan dan memberikan rekomendasi pekerjaan yang sesuai dengan keterampilan dan pengalaman kandidat.

## Daftar Isi
1. [Requirements](https://github.com/anggagilang11/Fourtastic/blob/main/requirements.txt)
2. [Instalasi](https://github.com/anggagilang11/Fourtastic?tab=readme-ov-file#instalasi)
3. [Cara Penggunaan](https://github.com/anggagilang11/Fourtastic?tab=readme-ov-file#cara-penggunaan)
4. [Dataset](https://github.com/anggagilang11/Fourtastic/tree/main/Data)
5. [Project Workflow](https://github.com/anggagilang11/Fourtastic?tab=readme-ov-file#project-workflow)

## Goal
Mengoptimalkan model machine learning yang dapat mengklasifikasikan kategori kalimat ke dalam salah satu kelas yang diberikan dalam training dataset yang disediakan.

## Instalasi
Untuk menginstal dan menjalankan proyek ini di komputer Anda, ikuti langkah-langkah berikut:
**1. Clone Repositori**
Pertama, clone repositori ini ke komputer Anda dengan menggunakan perintah berikut:

```bash
git clone https://github.com/anggagilang11/Fourtastic.git
```
**2. Masuk ke Direktori Proyek**
```
cd Fourtastic
```

**3. Instalasi Dependensi**
```
pip install -r requirements.txt
```

## Cara Penggunaan
**1. Clone Repositori Fork ke Komputer Lokal**
```
git clone https://github.com/USERNAME/Fourtastic.git
```
**2. Buat Cabang Baru (Branch)**
```
git checkout -b nama_cabang_baru
```
**3. Lakukan Perubahan di Local Computer**
**4. Menambahkan Perubahan ke Staging Area**
```
git add .   #menambahkan semua perubahan yang telah kamu buat ke staging area
git add nama_file.py   #jika hanya ingin menambahkan file tertentu
```
**5. Commit Perubahan**
```
git commit -m "Deskripsi singkat tentang perubahan"
```
**6. Push Perubahan Ke GitHub**
```
git push origin nama_cabang_baru
```


## Dataset
### Features
- Sentence_id: Kode unik untuk setiap kalimat.
- New_Sentence: Kalimat panjang yang berisi deskripsi pekerjaan.

### Target
- Type: Kategori dari New_Sentence, dengan label:
  - Requirements
  - Education
  - Skill
  - Softskill
  - Responsibility
  - Experience


## Project Workflow
**1. Exploratory Data Analysis (EDA):[here](https://github.com/anggagilang11/Fourtastic/blob/main/EDA_FOURTASTIC.ipynb)**
- Melakukan analisis distribusi kata dan kategori.
- Visualisasi distribusi data untuk memahami proporsi kategori.

**2. Prepocessing:**
- Menghapus stopwords.
- Menganalisis sentiment 
- Encoding label pada kolom Type.
- Handle class imbalance


**3. Modeling:**

Tahap ini belum dilakukan


**4. Evaluation & Deployment:**

Tahap ini belum dilakukan