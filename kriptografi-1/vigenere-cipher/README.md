# Vigenere Cipher

Aplikasi GUI berbasis **Python + Tkinter** untuk melakukan **enkripsi dan dekripsi Vigenere Cipher**, yaitu metode **substitusi abjad-majemuk** dalam kriptografi klasik.

## Deskripsi

Vigenere Cipher menggunakan sebuah kata sebagai kunci untuk menentukan besar pergeseran setiap karakter. Kunci akan digunakan secara berulang sepanjang pesan yang diproses.

Dalam aplikasi ini, posisi kunci hanya berpindah ketika karakter pada pesan merupakan huruf alfabet. Dengan demikian, spasi dan karakter non-alfabet tidak memengaruhi posisi kunci.

## Rumus

**Enkripsi:**

```text
c_i = (p_i + k_i) mod 26
```

**Dekripsi:**

```text
p_i = (c_i - k_i) mod 26
```

Keterangan:

* `p_i` = posisi karakter plaintext.
* `c_i` = posisi karakter ciphertext.
* `k_i` = nilai karakter kunci.
* `mod 26` = operasi modulo berdasarkan jumlah huruf alfabet.

## Fitur

*  **Enkripsi** menggunakan Vigenere Cipher.
*  **Dekripsi** ciphertext menggunakan kunci yang sesuai.
*  Mendukung **kata kunci berupa huruf A-Z**.
*  Kunci otomatis diulang mengikuti panjang pesan.
*  Mempertahankan penggunaan **huruf besar dan huruf kecil**.
*  **Salin Hasil** untuk menyalin output.
*  **Bersihkan** untuk menghapus input dan hasil.

## Teknologi

* **Python 3**
* **Tkinter**
* **ttk**
* **Messagebox**

## Cara Menjalankan

Pastikan Python telah terpasang pada komputer, kemudian jalankan:

```bash
python vigenere_cipher.py
```

Setelah program dijalankan, aplikasi GUI Vigenere Cipher akan terbuka.

## Cara Menggunakan

1. Masukkan plaintext atau ciphertext pada kolom **Teks Input**.
2. Masukkan kata kunci pada bagian **Kunci**.
3. Pastikan kunci hanya menggunakan huruf alfabet `A-Z`.
4. Pilih **Enkripsi** untuk menghasilkan ciphertext.
5. Pilih **Dekripsi** untuk mengembalikan ciphertext menjadi plaintext.
6. Gunakan **Salin Hasil** jika ingin menyalin output.

## Contoh

Pesan:

```text
she sells sea shells by the seashore
```

Kunci:

```text
KEY
```

Hasil enkripsi:

```text
CLC CIJVW QOE QRIJVW ZI XFO WCKWFYVC
```

Kunci `KEY` akan digunakan secara berulang selama proses enkripsi, sedangkan spasi pada pesan tetap dipertahankan dan tidak menyebabkan perpindahan posisi kunci.

## Catatan

Program memproses karakter alfabet `A-Z` dan `a-z`. Karakter selain alfabet, seperti spasi dan tanda baca, tidak mengalami perubahan dan **tidak membuat posisi kunci berpindah**.

---

**Tugas Kriptografi — Cipher Klasik**
