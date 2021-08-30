# Topological Sorter

#### Deskripsi singkat
Strategi algoritma decrease and conquer untuk algoritma topological sorting diimplementasikan dengan:
1. Membaca file soal lalu mengubahnya ke list representasi DAG (adjacency list).
2. Mencari mata kuliah (node) yang syaratnya sudah terpenuhi (tidak ada sisi yang berakhir di node itu).
3. Simpan node-node itu sebagai mata kuliah yang dapat diambil untuk semester pertama lalu hapus node itu dari DAG.
4. Ulang langkah 2 dan 3 dengan sisa DAG sampai tidak ada node lagi di DAG.
Program ini dibuat untuk tugas kecil 2 mata kuliah Strategi Algoritma
#### Requirement
Python 3.8 (dicoba di versi ini, pada versi python lain mungkin berbeda hasilnya)

Modul os dan pathlib dari Python

Soal berupa file .txt

#### Cara menggunakan
Run program sorter.py yang berada di folder src.

Run dapat dilakukan dengan command:

python src/sorter.py, command dapat diubah berdasarkan directory penjalanan program

Untuk mengubah input soal, ubah bagian namafile di file 13519096.py dengan nama file .txt yang diinginkan

#### Author
Nama: Girvin Junod

NIM: 13519096

Kelas: 02


