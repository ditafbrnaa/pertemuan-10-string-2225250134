# Pertemuan 10 String dan Pengolahan Teks

Nama: Amandita Pebriana Putri  
NIM: 2225250134  
Kelas: 3A Pendidikan Matematika  

## Tujuan
Mengolah dan menormalisasi data teks nama mahasiswa serta kode kelas yang memiliki format tidak konsisten menggunakan string Python.

## Cara Menjalankan
python3 tugas/normalisasi_data_mahasiswa.py

## Algoritma
1. Membaca data input nama dan kode kelas sebagai string dari pengguna.
2. Normalisasi nama dengan menghapus spasi berlebih menggunakan strip dan diubah menjadi format title case menggunakan title.
3. Memecah nama menjadi list kata menggunakan split, lalu membangun inisial dari karakter awal setiap kata[cite: 12].
4. Normalisasi kode kelas dengan strip, upper, split, dan menggabungkannya kembali menggunakan join serta tanda hubung [-].
5. Menampilkan hasil normalisasi secara rapi ke layar terminal.

## Test Case
| Input Nama | Input Kode | Hasil Utama yang Diharapkan | Status |
| :--- | :--- | :--- | :---: |
| aan hendrayana | pmat a 2026 | Nama: Aan Hendrayana / Kode: PMAT-A-2026 / Inisial: AH | Sesuai |
| fATHIYYAH MUTHMAINNAH | kelas b | Nama: Fathiyyah Muthmainnah / Kode: KELAS-B / Inisial: FM | Sesuai |
| BUDI | pmtk 01 | Nama: Budi / Kode: PMTK-01 / Inisial: B | Sesuai |
| siti nur aisyah | kelas c | Nama: Siti Nur Aisyah / Kode: KELAS-C / Inisial: SNA | Sesuai |
| AMANDITA PEBRIANA PUTRI | 3A | Nama: Amandita Pebriana Putri / Kode: 3A / Inisial: APP | Sesuai |

## Refleksi
String bersifat immutable sehingga tidak bisa diubah langsung pada indeks tertentu. Kendala spasi berlebih dan perbedaan huruf besar/kecil dapat diselesaikan menggunakan kombinasi method strip, lower, upper, title, split, dan join