# Perkalian Dua Matriks

Proyek ini merupakan implementasi operasi **perkalian dua matriks** menggunakan bahasa pemrograman Python sebagai bagian dari tugas **Proyek Aljabar Linear**.

Program memungkinkan pengguna untuk memasukkan dua buah matriks, kemudian menghitung hasil perkalian kedua matriks tersebut apabila ukuran/ordo matriks memenuhi syarat perkalian matriks.

## 📌 Deskripsi

Perkalian matriks merupakan salah satu operasi dasar dalam Aljabar Linear. Dua matriks dapat dikalikan apabila:

> **Jumlah kolom matriks pertama = jumlah baris matriks kedua.**

Misalnya:

- Matriks **A** berordo `m × n`
- Matriks **B** berordo `n × p`

Maka hasil perkalian:

**A × B = C**

akan menghasilkan matriks **C** berordo:

`m × p`

Setiap elemen pada matriks hasil diperoleh dengan menjumlahkan hasil perkalian elemen pada baris matriks pertama dengan elemen pada kolom matriks kedua.

Secara matematis:

`Cᵢⱼ = Σ(Aᵢₖ × Bₖⱼ)`

## 🎯 Tujuan

Proyek ini bertujuan untuk:

1. Memahami konsep perkalian dua matriks.
2. Memahami syarat dua matriks agar dapat dikalikan.
3. Mengimplementasikan operasi perkalian matriks menggunakan Python.
4. Menerapkan konsep perulangan dan struktur data list dalam Python.
5. Menghasilkan program sederhana yang dapat menerima input matriks dari pengguna.

## ⚙️ Cara Kerja Program

Secara umum, program bekerja dengan langkah-langkah berikut:

1. Pengguna memasukkan ukuran matriks pertama.
2. Pengguna memasukkan elemen-elemen matriks pertama.
3. Pengguna memasukkan ukuran matriks kedua.
4. Pengguna memasukkan elemen-elemen matriks kedua.
5. Program memeriksa apakah kedua matriks memenuhi syarat perkalian.
6. Jika memenuhi, program melakukan proses perkalian matriks.
7. Program menampilkan matriks hasil.
8. Jika tidak memenuhi syarat, program memberikan informasi bahwa kedua matriks tidak dapat dikalikan.

## 📐 Contoh Perhitungan

Diberikan:

```text
A = [ 1  2 ]
    [ 3  4 ]

B = [ 5  6 ]
    [ 7  8 ]
```

Perkalian:

```text
A × B
```

Elemen baris pertama kolom pertama:

```text
(1 × 5) + (2 × 7)
= 5 + 14
= 19
```

Elemen baris pertama kolom kedua:

```text
(1 × 6) + (2 × 8)
= 6 + 16
= 22
```

Sehingga hasilnya:

```text
C = [ 19  22 ]
    [ 43  50 ]
```

## 💻 Teknologi yang Digunakan

- **Python 3**
- List / Nested List
- Perulangan `for`
- Percabangan `if`
- Fungsi Python

## 📂 Struktur Repository

```text
perkalian-matriks/
│
├── perkalian_matriks.py
└── README.md
```

## ▶️ Cara Menjalankan

Pastikan Python 3 sudah terpasang pada komputer.

Clone repository:

```bash
git clone https://github.com/RasyaNabhanAlfathoni/Perkalian2Matriks.git
```

Masuk ke direktori repository:

```bash
cd proyek_1
```

Jalankan program:

```bash
python perkalianMatriks.py
```

## 🧪 Contoh Output

```text
=== PERKALIAN DUA MATRIKS ===

Masukkan jumlah baris matriks A: 2
Masukkan jumlah kolom matriks A: 2

Masukkan elemen matriks A:
1 2
3 4

Masukkan jumlah baris matriks B: 2
Masukkan jumlah kolom matriks B: 2

Masukkan elemen matriks B:
5 6
7 8

Hasil perkalian matriks A × B:

19 22
43 50
```

## 👥 Anggota Kelompok

| No. | Nama           |
| --- | -------------- |
| 1.  | Bintang Fitra  |
| 2.  | Favian Rasya   |
| 3.  | Raihan Rasyid  |
| 4.  | Rasya Nabhan   |
| 5.  | Talitha Farras |

## 📚 Materi

Konsep yang digunakan dalam proyek ini meliputi:

- Matriks
- Ordo matriks
- Baris dan kolom
- Perkalian matriks
- Operasi penjumlahan dan perkalian bilangan
- Perulangan bersarang (_nested loop_)
- Struktur data _nested list_

## 📄 Lisensi

Proyek ini dibuat untuk keperluan pembelajaran dan tugas **Aljabar Linear**.
