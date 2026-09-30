# Rail Fence Cipher

Aplikasi GUI berbasis **Python + Tkinter** yang digunakan untuk melakukan proses **enkripsi dan dekripsi Rail Fence Cipher**, yaitu salah satu metode **cipher transposisi** dalam kriptografi klasik.

## Deskripsi

Rail Fence Cipher bekerja dengan menyusun plaintext secara **zig-zag pada sejumlah baris (`k`)**, kemudian membaca karakter **baris demi baris** untuk menghasilkan ciphertext.

Pada implementasi ini, karakter spasi dihilangkan sebelum proses enkripsi, sehingga hasil dekripsi juga tidak mengandung spasi.

## Fitur

*  **Enkripsi** Rail Fence Cipher.
*  **Dekripsi** ciphertext menggunakan jumlah baris yang sama.
*  **Visualisasi zig-zag** untuk melihat proses penyusunan plaintext.
*  **Salin Hasil** untuk menyalin output dengan mudah.
*  **Bersihkan** untuk menghapus input, hasil, dan visualisasi.
*  Pengaturan jumlah baris (`k`) dengan nilai minimal **2**.

## Teknologi

* **Python 3**
* **Tkinter**
* **ttk**
* **Messagebox**

## Cara Menjalankan

Pastikan Python telah terpasang pada komputer, kemudian jalankan:

```bash
python railfence_cipher.py
```

Setelah perintah dijalankan, aplikasi GUI Rail Fence Cipher akan terbuka.

## Cara Menggunakan

1. Masukkan plaintext atau ciphertext pada kolom **Teks Input**.
2. Tentukan **Jumlah Baris (`k`)**.
3. Klik **Enkripsi** untuk menghasilkan ciphertext.
4. Klik **Dekripsi** untuk mengembalikan ciphertext ke plaintext.
5. Lihat bagian **Visualisasi Zig-Zag** untuk melihat susunan karakter pada rail.
6. Gunakan **Salin Hasil** untuk menyalin output.

## Contoh

Plaintext:

```tex
```
