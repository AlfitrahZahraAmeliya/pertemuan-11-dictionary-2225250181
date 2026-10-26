# Pertemuan 11 - Dictionary/Map

Nama: Alfitrah Zahra Ameliya  
NIM: 2225250181  
Kelas: 3B

## Tujuan

Memodelkan data pendidikan menggunakan dictionary dan pasangan key-value.

## Struktur Data

Program menggunakan dictionary `data_mahasiswa` dengan NIM sebagai key utama. Setiap value berupa dictionary yang berisi nama, kelas, dan nilai mahasiswa. Program menggunakan fungsi `cari_mahasiswa()` untuk mencari data berdasarkan NIM dan `rata_rata_nilai()` untuk menghitung rata-rata nilai mahasiswa.

## Cara Menjalankan

```bash
python praktik/data_mahasiswa.py
```

## Test Case

| Kasus | Hasil yang diharapkan | Hasil aktual | Status |
|---|---|---|---|
| Pencarian A003 | Data Citra ditampilkan | Data Citra ditemukan | Berhasil |
| Pencarian A999 | Pesan Data tidak ditemukan | Data tidak ditemukan | Berhasil |
| Pembaruan nilai A002 | Nilai berubah menjadi 82 | Nilai A002 menjadi 82 | Berhasil |
| Penambahan A006 | Key A006 tersedia | Data A006 berhasil ditambahkan | Berhasil |
| Rekap menggunakan `items()` | Semua NIM dan data tampil | A001–A006 ditampilkan | Berhasil |
| Rata-rata nilai | Rata-rata dihitung dengan benar | 83.50 | Berhasil |

## Refleksi

Salah satu kesalahan yang dapat terjadi saat menggunakan dictionary adalah mengakses key yang tidak tersedia sehingga menimbulkan `KeyError`. Kesalahan ini dapat dihindari dengan menggunakan metode `get()` agar program dapat memberikan pesan ketika data tidak ditemukan.