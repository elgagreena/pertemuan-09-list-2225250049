# Pertemuan 09 - List dan Pengolahan Data Numerik

## Identitas

* Nama: Elga Greena Rahma Tazkia
* NIM: 2225250049
* Kelas: 3B

## Tujuan

Memahami penggunaan list dalam Python untuk menyimpan, mengakses, memanipulasi, dan mengolah kumpulan data numerik.

## Struktur Program

* `latihan/01_buat_list.py`: Membuat list dan menghitung jumlah elemen.
* `latihan/02_indeks_slicing.py`: Mengakses elemen menggunakan indeks dan slicing.
* `latihan/03_manipulasi_list.py`: Mengubah, menambah, menyisipkan, dan menghapus elemen list.
* `latihan/04_agregasi_nilai.py`: Menghitung total, rata-rata, nilai minimum, dan maksimum.
* `latihan/05_filter_kelulusan.py`: Memilih nilai yang memenuhi batas kelulusan.
* `latihan/06_fungsi_statistik.py`: Menghitung rata-rata menggunakan fungsi.
* `praktik/analisis_nilai_mahasiswa.py`: Mengolah nilai mahasiswa dan menampilkan ringkasan statistik.

## Cara Menjalankan

Jalankan perintah berikut melalui terminal dari folder proyek:

```bash
python praktik/analisis_nilai_mahasiswa.py
```

## Test Case

| Pengujian          | Data           | Hasil yang Diharapkan      | Status   |
| ------------------ | -------------- | -------------------------- | -------- |
| Rata-rata          | `[60, 70, 80]` | `70.0`                     | Berhasil |
| Nilai minimum      | `[60, 70, 80]` | `60`                       | Berhasil |
| Nilai maksimum     | `[60, 70, 80]` | `80`                       | Berhasil |
| Jumlah nilai lulus | `[60, 70, 80]` | `3`                        | Berhasil |
| Batas kelulusan    | `[59, 60, 61]` | `[60, 61]`                 | Berhasil |
| Data kosong        | `[]`           | Rata-rata `0`, tanpa error | Berhasil |

## Refleksi

Saya memahami bahwa indeks digunakan untuk mengakses elemen tertentu dalam list, dengan indeks pertama dimulai dari `0`. Salah satu kesalahan yang berhasil diperbaiki adalah penggunaan indeks yang tidak sesuai saat mengakses elemen list. Kesalahan tersebut diperbaiki dengan menyesuaikan indeks agar elemen yang diakses sesuai dengan posisi yang diinginkan.

