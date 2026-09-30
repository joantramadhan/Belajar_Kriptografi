# Caesar Cipher

Aplikasi GUI berbasis **Python + Tkinter** untuk melakukan proses **enkripsi dan dekripsi Caesar Cipher** sebagai bagian dari tugas mata kuliah Kriptografi.

## Deskripsi

Caesar Cipher merupakan metode substitusi sederhana yang menggeser posisi setiap huruf pada alfabet berdasarkan nilai kunci tertentu.

### Rumus

**Enkripsi:**

```text
c = (p + k) mod 26
```

**Dekripsi:**

```text
p = (c - k) mod 26
```

Keterangan:

* `p` = posisi huruf plaintext
* `c` = posisi huruf ciphertext
* `k` = nilai pergeseran/kunci

## Fitur Aplikasi

*  **Enkripsi** — mengubah plaintext menjadi ciphertext.
*  **Dekripsi** — mengembalikan ciphertext menjadi plaintext.
*  **Brute Force** — mencoba seluruh kemungkinan kunci dari `0` hingga `25`.
*  **Salin Hasil** — menyalin hasil pemrosesan ke clipboard.
*  **Bersihkan** — menghapus input dan hasil.
*  Mempertahankan format **huruf besar dan huruf kecil**.
*  **Angka, spasi, dan tanda baca tidak mengalami perubahan**.

## Teknologi

* **Python 3**
* **Tkinter**
* **ttk**
* **Messagebox**

## Cara Menjalankan

Pastikan Python sudah terinstall pada komputer.

Kemudian jalankan perintah berikut melalui terminal:

```bash
python caesar_cipher.py
```

Setelah berhasil dijalankan, jendela aplikasi Caesar Cipher akan terbuka.

## Cara Menggunakan

1. Masukkan plaintext atau ciphertext pada kolom **Teks Input**.
2. Masukkan nilai kunci pada bagian **Kunci (k)**.
3. Pilih **Enkripsi** atau **Dekripsi**.
4. Hasil akan ditampilkan pada bagian **Hasil**.
5. Gunakan **Salin Hasil** jika ingin menyalin output.
6. Untuk mencoba seluruh kemungkinan kunci, gunakan tombol **Brute Force**.

### Contoh

Dengan plaintext:

```text
HELLO WORLD
```

dan kunci:

```text
3
```

hasil enkripsinya:

```text
KHOOR ZRUOG
```

Kemudian ciphertext tersebut dapat didekripsi kembali menggunakan kunci `3` untuk mendapatkan plaintext awal.

## Catatan

Program hanya melakukan pergeseran terhadap karakter alfabet `A-Z` dan `a-z`. Karakter selain alfabet, seperti angka, spasi, dan tanda baca, akan tetap dipertahankan.

---

**Tugas Kriptografi — Cipher Klasik**
