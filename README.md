# Tree
•	Kumpulan node yang saling terhubung satu sama lain dalam suatu kesatuan yang membentuk layakya struktur sebuah pohon.
•	Struktur pohon adalah suatu cara merepresentasikan suatu struktur hirarki (one-to-many) secara grafis yang mirip sebuah pohon, walaupun pohon tersebut hanya tampak sebagai kumpulan node-node dari atas ke bawah.

## Terminologi Tree
![terminologi-tree](https://4.bp.blogspot.com/-kRRhE_q3Rrs/WlmGpBrKlJI/AAAAAAAABRc/evU6gm5v-8UCbJeN8EQ8Tf21B-p_uYA2gCLcBGAs/s1600/Capture.JPG)

## Contoh Tree
![ContohTree](https://image3.slideserve.com/5744899/contoh-tree-silsilah-keluarga-l.jpg)

## Operasi-Operasi Tree
1. `Create`: Membentuk sebuah tree baru yang kosong.
2. `Clear`: Menghapus semua elemen tree.
3. `Empty`: Mengetahui apakah tree kosong atau tidak.
4. `Insert`: Menambah node ke dalam Tree secara rekursif.
5. `Find`: Mencari node di dalam Tree secara rekursif sampai node tersebut ditemukan dengan menggunakan variable bantuan ketemu. 
6. `Traverse`: yaitu operasi kunjungan terhadap node-node dalam pohon dimana masing-masing node akan dikunjungi sekali.
7. `Count`: Menghitung jumlah node dalam Tree.
8. `Height`: Mengetahui kedalaman sebuah Tree.
9. `•Find Min dan Find Max`: Mencari nilai terkecil dan terbesar pada tree.
10. `Child`: Mengetahui anak dari sebuah node (jika punya).

## Jenis Transverse 
* `PreOrder`: cetak node yang dikunjungi, kunjungi left, kunjungi right (tengah, kiri, kanan)
* `InOrder`: kunjungi left, cetak node yang dikunjungi, kunjungi right (kiri, tengah, kanan)
* `PostOrder`: kunjungi left, kunjungi right cetak node yang dikunjungi (kiri, kanan, tengah)

