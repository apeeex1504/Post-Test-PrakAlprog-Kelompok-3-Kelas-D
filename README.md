# 📊 Postes Kelompok 6 - Praktikum Algoritma dan Pemrograman 2026

## 📖 Deskripsi Proyek

Proyek ini merupakan tugas **Postes Praktikum Algoritma dan Pemrograman 2026** yang berfokus pada analisis dan visualisasi data menggunakan bahasa pemrograman Python.

Dataset yang digunakan adalah **Happiness and Satisfaction Dataset**, yang berisi informasi mengenai tingkat kebahagiaan, kepuasan hidup, pendapatan, ketimpangan ekonomi, GDP, serta wilayah dari berbagai negara di dunia.

Analisis dilakukan melalui beberapa tahapan, yaitu agregasi data, filtering data, analisis korelasi, dan analisis distribusi data yang kemudian divisualisasikan menggunakan berbagai jenis grafik.

---

## 🎯 Tujuan Proyek

* Mempelajari teknik manipulasi data menggunakan Python.
* Mengimplementasikan visualisasi data menggunakan Matplotlib dan Seaborn.
* Menganalisis hubungan antara variabel ekonomi dan tingkat kepuasan hidup.
* Mengembangkan kemampuan kolaborasi menggunakan Git dan GitHub.

---

## 🛠️ Tools dan Library

* Python 3.x
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook
* Git & GitHub

### Instalasi Library

```bash
pip install pandas matplotlib seaborn
```

---

## 📂 Struktur Repository

```text
📦 Postes-Kelompok-6-PrakAlprog-2026
│
├── Kategori A.ipynb
├── Kategori B.ipynb
├── Kategori C.ipynb
├── Kategori D.ipynb
├── Kelas D_Happiness and Satisfaction.csv
└── README.md
```

---

# 📋 Pembagian Tugas Kelompok (Jobdesk)

Untuk memastikan proyek berjalan secara terstruktur dan adil, setiap anggota kelompok diberikan tanggung jawab sesuai dengan sub-tugas yang telah ditentukan.

---

### 🧑‍💻 Betram Limbong

**Kategori A – Visualisasi Hasil Agregasi**

**Tugas:**

* Melakukan manipulasi dan agregasi data untuk menghitung jumlah negara pada setiap region.
* Mengelompokkan data berdasarkan wilayah (*Region*).
* Membuat visualisasi menggunakan **Pie Chart**.
* Mengunggah dataset awal ke repositori GitHub.

---

### 🧑‍💻 Muhammad Mycho Herlambang

**Kategori B – Visualisasi Hasil Filter**

**Tugas:**

* Melakukan filtering data pada region **Central and Eastern Europe**.
* Mengurutkan nilai **income inequality** dari yang terendah.
* Mengidentifikasi negara dengan tingkat pemerataan ekonomi terbaik.
* Menampilkan hasil analisis menggunakan **Bar Chart**.

---

### 🧑‍💻 Malvin Marchiano Rittho

**Kategori C – Visualisasi Hasil Korelasi**

**Tugas:**

* Melakukan analisis hubungan antara **GDP** dan **Average Satisfaction (0-10)**.
* Menghitung serta menginterpretasikan hubungan korelasi kedua variabel.
* Membuat visualisasi menggunakan **Scatter Plot**.

---

### 🧑‍💻 Muhammad Fabian Novansyah

**Kategori D – Visualisasi Hasil Distribusi**

**Tugas:**

* Mengambil data pada kolom **Happy Score (0-10)**.
* Menganalisis pola persebaran skor kebahagiaan global.
* Membuat visualisasi menggunakan **Histogram + KDE**.

---

### 🧑‍💻 Rassya Apriansyah (Ape)

**Manajemen, Integrasi, dan Dokumentasi**

**Tugas:**

* Bertindak sebagai Repository Administrator.
* Mengelola struktur repositori GitHub.
* Membuat dan mengelola dokumentasi README.
* Melakukan code review terhadap seluruh program.
* Mengintegrasikan seluruh kode Kategori A, B, C, dan D menjadi satu notebook utama.
* Membuat visualisasi gabungan menggunakan subplot 2×2.
* Menyusun laporan akhir kelompok.

---

# 🚀 Alur Kerja Kolaborasi GitHub

1. Setiap anggota mengerjakan tugas sesuai kategori masing-masing.
2. Kode program dan hasil visualisasi diunggah ke repositori GitHub.
3. Setiap perubahan dicatat menggunakan commit message yang jelas.
4. Repository Administrator melakukan code review.
5. Seluruh kode dari Kategori A sampai D digabungkan menjadi satu notebook utama.
6. Visualisasi gabungan dibuat menggunakan fungsi:

```python
plt.subplots(2, 2, figsize=(12,10))
```

7. Dokumentasi proyek dan laporan akhir disusun sebelum pengumpulan tugas.

---

# 📈 Kategori A - Visualisasi Hasil Agregasi

## Tujuan

Menghitung jumlah negara pada masing-masing region dan menampilkannya dalam bentuk Pie Chart.

## Metode

1. Membaca dataset.
2. Mengelompokkan data berdasarkan Region.
3. Menghitung jumlah negara pada setiap region.
4. Menampilkan hasil dalam Pie Chart.

## Output

✅ Pie Chart distribusi jumlah negara berdasarkan region.

---

# 📊 Kategori B - Visualisasi Hasil Filter

## Tujuan

Menampilkan negara-negara dari wilayah Central and Eastern Europe dengan nilai income inequality paling rendah.

## Metode

1. Memfilter data berdasarkan region.
2. Mengurutkan data berdasarkan income inequality.
3. Mengambil nilai terendah.
4. Menampilkan hasil menggunakan Bar Chart.

## Output

✅ Bar Chart negara dengan income inequality terendah.

---

# 📉 Kategori C - Visualisasi Hasil Korelasi

## Tujuan

Menganalisis hubungan antara GDP dan Average Satisfaction (0-10).

## Metode

1. Mengambil data GDP.
2. Mengambil data Average Satisfaction.
3. Menghitung hubungan kedua variabel.
4. Menampilkan Scatter Plot.

## Output

✅ Scatter Plot hubungan GDP dan tingkat kepuasan hidup.

## Interpretasi

Semakin tinggi GDP suatu negara, umumnya tingkat kepuasan hidup masyarakat cenderung meningkat.

---

# 📋 Kategori D - Visualisasi Hasil Distribusi

## Tujuan

Menampilkan distribusi nilai Happy Score dari seluruh negara.

## Metode

1. Mengambil data Happy Score.
2. Menganalisis persebaran data.
3. Menampilkan Histogram dan KDE.

## Output

✅ Histogram + KDE distribusi Happy Score global.

---

# 📊 Grafik Gabungan (Kategori E)

Grafik gabungan dibuat menggunakan fungsi:

```python
fig, ax = plt.subplots(2,2, figsize=(12,10))
```

### Layout Visualisasi

```text
┌───────────────────┬───────────────────┐
│ Grafik A          │ Grafik B          │
│ Pie Chart         │ Bar Chart         │
├───────────────────┼───────────────────┤
│ Grafik C          │ Grafik D          │
│ Scatter Plot      │ Histogram + KDE   │
└───────────────────┴───────────────────┘
```

Visualisasi ini bertujuan untuk menampilkan seluruh hasil analisis dalam satu tampilan yang lebih ringkas dan mudah dipahami.

---

## 🌟 Kontribusi Anggota

| Nama                      | Kategori                | Visualisasi     |
| ------------------------- | ----------------------- | --------------- |
| Betram Limbong            | A                       | Pie Chart       |
| Muhammad Mycho Herlambang | B                       | Bar Chart       |
| Malvin Marchiano Rittho   | C                       | Scatter Plot    |
| Muhammad Fabian Novansyah | D                       | Histogram + KDE |
| Rassya Apriansyah         | Integrasi & Dokumentasi | Subplots (2×2)  |

---

# 🎯 Kesimpulan

Berdasarkan analisis dan visualisasi yang telah dilakukan, diperoleh beberapa kesimpulan:

1. Jumlah negara pada setiap region tidak tersebar secara merata.
2. Terdapat negara-negara dengan tingkat ketimpangan ekonomi yang lebih rendah dibandingkan negara lainnya dalam region yang sama.
3. GDP menunjukkan hubungan positif terhadap tingkat kepuasan hidup masyarakat.
4. Distribusi Happy Score memperlihatkan variasi tingkat kebahagiaan antar negara.
5. Visualisasi data membantu proses analisis menjadi lebih informatif dan mudah dipahami dibandingkan data mentah.

---

## 📚 Referensi

* Modul Praktikum Algoritma dan Pemrograman 2026
* Dataset Happiness and Satisfaction
* Dokumentasi Pandas
* Dokumentasi Matplotlib
* Dokumentasi Seaborn
* Repository Referensi Praktikum
