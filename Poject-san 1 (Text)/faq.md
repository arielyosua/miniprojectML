

## ❓ FAQ – Penggunaan Dataset Teks (Tweet)

---

### 🔹 1. Apa isi dari dataset yang digunakan?

Dataset terdiri dari dua bagian utama:

- **Labeled Dataset**: tweet yang sudah dilengkapi dengan label kategori/topik yang benar (ground truth). Dataset ini digunakan untuk **evaluasi performa model**.
- **Unlabeled Dataset**: tweet yang hanya berisi teks tanpa label. Dataset ini digunakan untuk **melakukan klasifikasi secara langsung**.

---

### 🔹 2. Apa perbedaan peran antara labeled dan unlabeled dataset?

- **Labeled Dataset** digunakan untuk:
  - Menghitung metrik evaluasi seperti akurasi, precision, recall, dll.
  - Melihat seberapa baik hasil klasifikasi mendekati ground truth.

- **Unlabeled Dataset** digunakan untuk:
  - Menguji model terhadap data yang belum diberi label.
  - Melakukan klasifikasi untuk mendapatkan prediksi kategori.

---

### 🔹 3. Format atau struktur dataset-nya seperti apa?

**Labeled Dataset**:
- `tweet`: teks tweet
- `label`: kategori/topik dari tweet

**Unlabeled Dataset**:
- `id`: ID unik tweet
- `tweet`: teks tweet saja, **tanpa kolom label**

---

### 🔹 4. Apa yang harus dilakukan terhadap dataset sebelum digunakan?

- Pastikan kedua dataset telah dibersihkan dari duplikasi dan entri kosong.
- Lakukan preprocessing dasar (jika perlu), seperti menghapus URL, simbol, atau normalisasi teks, tergantung kebutuhan eksplorasi.

---

### 🔹 5. Bagaimana cara mencocokkan hasil klasifikasi dengan data berlabel?

Setelah melakukan klasifikasi terhadap labeled dataset, hasil prediksi dapat dibandingkan dengan kolom `label` untuk menghitung performa model.

---

### 🔹 6. Apakah saya boleh menggabungkan dua dataset ini?

**Tidak**

---

### 🔹 7. Apakah struktur kolom harus konsisten?

Ya. Kedua dataset minimal harus memiliki kolom `id` dan `tweet`. Labeled dataset memiliki tambahan kolom `label`.

---