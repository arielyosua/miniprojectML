
---

## 🎓 TUGAS KLASIFIKASI DATA  
**(Pilih Salah Satu: Klasifikasi Gambar atau Zero-Shot Klasifikasi Tweet)**

### 🔹 Deskripsi Tugas  
Tugas ini bertujuan untuk menerapkan metode klasifikasi pada jenis data tertentu. Mahasiswa **hanya diminta memilih salah satu** dari dua jenis tugas berikut:

1. **Klasifikasi Gambar** menggunakan salah satu model klasik  
2. **Zero-Shot Klasifikasi Tweet** menggunakan model klasik (cosine similiarity) atau transformer 

---

## ✨ PILIHAN 1 — KLASIFIKASI GAMBAR  

### Tujuan  
Melakukan klasifikasi gambar menggunakan **salah satu dari empat model berikut**:
- Decision Tree  
- Random Forest (Tree)  
- K-Nearest Neighbor (KNN)  
- Support Vector Machine (SVM)  

### Dataset  
Dataset berupa **data A** (gambar dengan beberapa kelas) — akan disediakan.

---

## ✨ PILIHAN 2 — ZERO-SHOT KLASIFIKASI TWEET  

### Tujuan  
Melakukan klasifikasi topik terhadap tweet menggunakan pendekatan **Zero-Shot Learning** dengan **model transformer**.

### Dataset  
Dataset berupa **data B** (tweet berbahasa Indonesia dengan label topik) — akan disediakan.

### Label Kandidat

```python
candidate_labels = [
    "Ideology",
    "Politics",
    "Economy",
    "Social Culture",
    "Defense and Security",
    "Natural Resources",
    "Geography",
    "Demographics"
]
```

---

## 🎯 KOMPONEN YANG WAJIB ADA (UNTUK KEDUA JENIS TUGAS)

| Komponen                               | Bobot |
|----------------------------------------|-------|
| 1. **EDA (Exploratory Data Analysis)** | 20%   |
| 2. **Preprocessing**                   | 20%   |
| 3. **Pemilihan Model & Training**      | 30%   |
| 4. **Evaluasi Model**                  | 20%   |
| 5. **Dokumentasi GitHub/Web**          | 10%   |

---

### 📌 Catatan Penting  
- Hanya **salah satu** tugas yang dikerjakan (gambar atau tweet).  
- Model yang digunakan untuk **zero-shot** boleh dari modedl transformer.  
- Untuk klasifikasi tweet, hasil prediksi akan dibandingkan dengan label ground truth yang disediakan.  
- Mahasiswa diminta menyusun alur dan pendekatan **secara mandiri**, sesuai kreativitas dan pemahamannya.
- Berikan dokumentasi yang lengkap dan technical report (Silahkan mencari referensi technical report yang baik).

---