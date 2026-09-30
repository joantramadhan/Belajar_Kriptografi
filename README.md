# TUGAS KRIPTOGRAFI

**Identitas Mahasiswa**
**Nama**: Joant Ramadhan
**NIM**: 312410594
**Kelas**: I241E
**Program Studi**: Teknik Informatika
**Mata Kuliah**: Kriptografi

# Implementasi Cipher Klasik

Project ini berisi tiga program cipher klasik yang dibuat menggunakan **Python dan Tkinter** sebagai bagian dari tugas mata kuliah Kriptografi.

| Program               | Algoritma         | Kategori                 | Bentuk Kunci                             |
| --------------------- | ----------------- | ------------------------ | ---------------------------------------- |
| `caesar_cipher.py`    | Caesar Cipher     | Substitusi               | Angka `k` dan tersedia fitur Brute Force |
| `vigenere_cipher.py`  | Vigenere Cipher   | Substitusi abjad-majemuk | Kata yang terdiri dari huruf A-Z         |
| `railfence_cipher.py` | Rail Fence Cipher | Transposisi              | Jumlah baris, minimal 2                  |

## Menjalankan Program

Pastikan Python sudah terpasang pada komputer, kemudian jalankan masing-masing program melalui terminal:

```bash
python caesar_cipher.py
```

```bash
python vigenere_cipher.py
```

```bash
python railfence_cipher.py
```

Setiap perintah akan membuka tampilan aplikasi berbasis Tkinter.

## Panduan Penggunaan

1. Masukkan pesan yang ingin diproses pada bagian **Teks Input**.
2. Tentukan kunci sesuai algoritma yang digunakan.
3. Pilih **Enkripsi** atau **Dekripsi** sesuai kebutuhan.
4. Hasil pemrosesan akan ditampilkan pada bagian **Hasil**.
5. Gunakan tombol **Salin Hasil** untuk menyalin hasil proses.
6. Program Caesar Cipher juga menyediakan fitur **Brute Force** untuk mencoba kunci `0–25`.

## Contoh Pengujian

### Caesar Cipher

Dengan `k = 3`:

```text
Input  : awasi asterix dan temannya obelix
Output : dzdvl dvwhula gdq whpdqqbd rehola
```

### Vigenere Cipher

Dengan keyword `KEY`:

```text
Input  : she sells sea shells by the seashore
Output : clc cijvw qoe qrijvw zi xfo wckwfyvc
```

### Rail Fence Cipher

Dengan jumlah baris `3`:

```text
Input  : CRYPTOGRAPHY AND DATA SECURITY
Output : CTAAAEIRPORPYNDTSCRTYGHDAUY
```

> **Catatan:** Rail Fence Cipher menghilangkan spasi selama proses enkripsi, sehingga hasil dekripsi ditampilkan tanpa spasi.
