# Praktikum 4
## Dekspripsi Tugas
- Buat sebuah list sebanyak 5 elemen dengan nilai bebas
- akses list:
  - tampilkan elemen ke 3
  - ambil nilai elemen ke 2 dengan elemen ke 4
  - ambil elemen terakhir
- ubah elemen list:
  - ubah elemen ke 4 dengan nilai lainnya
  - ubah elemen ke 4 sampai dengan elemen terakhir
- tambah elemen list:
  - ambil 2 bagian dari list pertama (A) dan jadikan list ke 2 (B)
  - tambah list B dengan nilai string
  - tambah list B dengan 3 nilai
  - gabungkan list B dengan list A

## Akses list
```python
# Membuat sebuah list dengan 5 elemen nilai bebas
my_list = [10, 20, 30, 40, 50]

# Akses elemen pada list
elemen_ke_3 = my_list[2]  # Tampilkan elemen ke-3
elemen_2_sampai_4 = my_list[1:4]  # Ambil nilai elemen ke-2 sampai ke-4
elemen_terakhir = my_list[-1]  # Ambil elemen terakhir

# Menampilkan hasil
print("Elemen ke-3:", elemen_ke_3)
print("Elemen ke-2 sampai ke-4:", elemen_2_sampai_4)
print("Elemen terakhir:", elemen_terakhir)
```
## Ubah elemen list
```python
# Membuat sebuah list dengan 5 elemen nilai bebas
my_list = [10, 20, 30, 40, 50]

# Ubah elemen ke-4
my_list[3] = 100  # Mengganti elemen ke-4 dengan nilai 100

# Ubah elemen ke-4 sampai dengan elemen terakhir
my_list[3:] = [200, 300]  # Mengganti elemen ke-4 sampai terakhir

# Menampilkan hasil akhir
print("List setelah perubahan:", my_list)
```
## Tambah elemen list
```python
# Membuat list pertama (A) dengan 5 elemen
A = [10, 20, 30, 40, 50]

# Ambil 2 bagian dari list pertama (A) dan jadikan list kedua (B)
B = A[:2]  # Mengambil dua elemen pertama dari A

# Tambah list B dengan nilai string
B.append("string_value")  # Menambahkan nilai string ke B

# Tambah list B dengan 3 nilai lainnya
B.extend([60, 70, 80])  # Menambahkan tiga nilai baru ke B

# Gabungkan list B dengan list A
gabungan = B + A

# Menampilkan hasil
print("List A:", A)
print("List B:", B)
print("Gabungan List B dan A:", gabungan)
```
## Ouput
![Screenshot 2024-11-16 162938](https://github.com/user-attachments/assets/8bd61274-8ef8-4b80-9629-4a3bf51118a0)
![Screenshot 2024-11-16 162954](https://github.com/user-attachments/assets/b198957e-c848-4704-8ab6-21c78ca136d1)
![Screenshot 2024-11-16 163009](https://github.com/user-attachments/assets/d014d94d-a2c9-400c-8733-3aa970d05ad3)

## Penjelasan
- Akses list
1. List: Dibuat list dengan 5 elemen [10, 20, 30, 40, 50].
2. Akses elemen ke-3: Menggunakan indeks 2 karena indeks dimulai dari 0.
3. Elemen ke-2 sampai ke-4: Menggunakan slicing my_list[1:4].
4. Elemen terakhir: Menggunakan indeks negatif -1.
- Ubah elemen list
1. Mengganti elemen ke-4: Menggunakan indeks 3 untuk mengganti nilai.
2. Mengganti elemen ke-4 sampai terakhir: Menggunakan slicing my_list[3:] untuk mengganti semua elemen mulai dari indeks 3 hingga akhir list.
- Tambah elemen list
1. List B: Dibuat dari dua elemen pertama list A menggunakan slicing A[:2].
2. Menambah string ke list B: Menggunakan append() untuk menambahkan satu elemen string.
3. Menambah tiga nilai baru ke list B: Menggunakan extend() untuk menambahkan beberapa elemen sekaligus.
4. Menggabungkan list: Menggunakan operator + untuk menggabungkan list B dengan list A.
