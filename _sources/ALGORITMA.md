---
title: ALGORITMA

---

# ALGORITMA
## Definisi Algoritma
Algoritma adalah suatu urutan instruksi yang disusun secara sistematis dan logis untuk menyelesaikan suatu masalah dan menghasilkan output tertentu

## Algoritma Sequential Search 
**Pencarian Berurutan (sequential search)** adalah pencarian yang membandingkan data yang ada satu per satu secara berurutan sampai data yang dicari ditemukan atau tidak ditemukan.
### Proses dalam Sequential Search : 
1. Pertama data melakukan perbandingan satu-persatu secara berurutan dalam kumpulan data dengan data yan dicari sampai data tersebut ditemukan atau tidak ditemukan.
2. Pada dasarnya,pencarian ini hanya melakukan pengulangan data dari 1 sampai jumlah data (n)
3. Setiap pengulangan,dibandingkan data ke-i dengan data yang dicari
4. apabila data sama dengan yang dicari,berarti data telah berhasil ditemukan.Sebaliknya apabila sampai akhir melakukan pengulangan tidak ada data yang sama dengan yan dicari,berarti data tidak ada yang ditemukan 

## Algoritma Binary Search
**Pencarian biner (Binary Search)** adalah algoritma pencarian yang digunakan untuk menemukan posisi nilai target dalam array yang diurutkan
### Proses dalam Binary Search
1. Pertama pengambilan data dimulai dari posisi posisi 1 samapai posisi akhir(n)
2. selanjutnya mencari posisi data yang tengah dengan menggunakan rumus : ( posisi awal + posisi akhir )/2
3. Setelah itu data yang akan dicari dibandingkan dengan data yang berada di tengah,apakah data tersebut sama apa lebih kecil, atau lebih besar?
4. Seandainya data tersebut lebih besar,maka proses pencarian yang dicari dengan posisi awal adalah posisi tengah +1
5. apabila data lebih kecil,maka proses pencarian yang dicari dengan posisi akhir adalah posisi tengah -1
6. jika data sama dengan data yang dicari,berarti data tersebut telah ketemu

## Pseudocode
Pseudocode adalah cara penulisan kode dan algoritma menggunakan bahasa umum yang digunakan sehari-hari sehingga lebih mudah dipahami. Karena itu pseudocode juga disebut sebagai false code atau representation code.

## Big O Algoritma
**Notasi Big O** adalah cara standar untuk mengekspresikan kompleksitas waktu atau ruang suatu algoritma. Notasi ini memungkinkan kita untuk memahami bagaimana kinerja suatu algoritma meningkat seiring dengan bertambahnya ukuran input 





#### Refrensi

* https://elektro.um.ac.id/wp-content/uploads/2016/04/Struktur-Data-Modul-Praktikum-3-Searching.pdf
* https://repository.unikom.ac.id/
* https://tirago4.wordpress.com/2016/10/11/pencarian-searching-didalam-algoritma/