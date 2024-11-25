---
title: deretan dan rekursif

---

# Deretan dan rekursi

## deretan
### pengertian deretan
deretan adalah suatu urutan atau susunan elemen atau objek yang disusun secara teratur berdasarkan suatu aturan tertentu. Elemen dalam deretan biasanya berupa angka, huruf, simbol, atau objek lainnya, dan urutannya dapat didasarkan pada pola, nilai, atau hubungan tertentu.

### definisi deretan
Sebuah deretan adalah fungsi dari subset suatu himpunan bilangan bulat (biasanya N atau P) ke sebuah himpunan S.

N = {1, 2, 3, 4, … }
   S misalnya {2, 4, 6, 8, …},   {1/3, 1/5, 1/7, …},  dsb

Notasi deretan: {an}

##
Deretan umumnya dinyatakan dalam suatu formula, misalnya:
	an = 2n
	an = 1/n
	an = 7 – 3n

## 
Dalam konteks matematika, deretan sering merujuk pada barisan bilangan, yaitu kumpulan bilangan yang disusun dalam suatu pola tertentu.
 Misalnya:
1. Deretan bilangan ganjil: 1,3,5,7,…
2. Deretan bilangan genap: 2,4,6,8,…
3. Deretan bilangan yang membentuk deret aritmetika: 3,6,9,12....

macam macam jenis deretean beserta prnjrlasan
penjumlahan deretan

## Contoh-contoh deretan dan formulanya:

### deret aritmatika
-contoh: 2,5,8,11,14, ,,,
-rumus suku ke-n:
    𝑈_𝑛=𝑎+(𝑛−1)⋅𝑏
 dimana:
-a:suku pertama
-𝑏: beda (selisih antar suku
-𝑛: nomor suku yang dicari

### deret geometri
## 
Deret dengan pola kelipatan tetap.
- Contoh: 3,6,12,24,48,…
- Rumus suku ke-n:
     𝑈_𝑛=𝑎⋅𝑟^((𝑛−1) )
## 
Di mana:
- 𝑎: suku pertama 
- 𝑟: rasio (perbandingan antar suku,
- 𝑛: nomor suku yang dicari

### deret bilangan kuadrat
Deret dengan pola nilai berupa kuadrat bilangan bulat.
- Contoh: 1,4,9,16,25,…
- Rumus suku ke-n:
    𝑈_𝑛=𝑛^2

### deret bilangan kubik
Deret dengan pola nilai berupa kubik bilangan bulat.
- Contoh: 1,8,27,64,125,…
- Rumus suku ke-n:
    𝑈_𝑛=𝑛^3

### Deret Fibonacci
Deret dengan pola di mana setiap suku merupakan jumlah dua suku sebelumnya.
- Contoh: 0,1,1,2,3,5,8,…
- Rumus suku ke-n(rekursif):
    𝐹_𝑛=𝐹_(𝑛−1)+𝐹_(𝑛−2),𝐹_0=0,𝐹_1=1

### String
adalah deretan berhingga karakter berbentuk
    ![image](https://hackmd.io/_uploads/S1da-nemJg.png)
    
Panjang string S adalah jumlah karakter di dalam string tersebut.

Contoh: informatika adalah string dengan panjang 11 karakter
	10100101 adalah string biner dengan panjang 8 bit

 ![image](https://hackmd.io/_uploads/ByuwGnx7kl.png)

## penjumlahan deretan
Jumlah deretan 
	am, am+1, am+2, …, an
  adalah
	 am + am+1 + am+2 + … + an
  atau dalam notasi sumasi:
	![image](https://hackmd.io/_uploads/r1mYQ2xQyx.png)

   
    k adalah indeks summasi, 
    m adalah batas bawah indeks,
    n adalah batas atas indeks
## 
Contoh 2: Berapa nilai![image](https://hackmd.io/_uploads/H1Ip73x71e.png)
 jawaban:
 ![image](https://hackmd.io/_uploads/HJfJ43lQ1e.png)

## 
Contoh 3: Batas bawah sumasi kadangkala perlu digeser agar dapat dijumlahkan dengan sumasi lain yang memiliki batas bawah berbeda. Pada contoh 2 di atas batas bawah digeser dari 1 menjadi 0, akibatnya:
    ![image](https://hackmd.io/_uploads/ByKzE2g7Je.png)

## 
Contoh 4: Sumasi dapat dipecah dengan membagi dua indeksnya, misalnya
![image](https://hackmd.io/_uploads/SyP4E2gXke.png)

## 
Contoh 5: Hitung nilai ![image](https://hackmd.io/_uploads/Sk8-H2x71e.png)
 jawaban:
 ![image](https://hackmd.io/_uploads/B1kwSnx7ye.png)

### sumasi ganda
Di dalam algoritma, kita perlu menghitung berapa kali suatu operasi tertentu dilakukan di dalam sebuah kalang bersarang (nested loop). Penjumlahan semua operasi di dalam kalang bersarang dinyatakan dalam bentuk sumasi ganda.

contoh: ![image](https://hackmd.io/_uploads/H14TrneQJl.png)

Untuk menghitung sumasi ganda, mula-mula ekspansi sumasi terdalam, lalu  dilanjukan dengan sumasi terluar:
![image](https://hackmd.io/_uploads/r1QJ83lm1e.png)

## rekursi
## 
Sebuah objek dikatakan rekursif  (recursive) jika ia didefinisikan dalam terminologi dirinya sendiri. 
## 
Proses mendefinisikan objek dalam terminologi dirinya sendiri disebut rekursi (recursion).
## 
Perhatikan tiga buah gambar pada tiga slide berikut ini.
## 
Objek fraktal  adalah contoh bentuk rekursif.
![image](https://hackmd.io/_uploads/Sk4cUnl7ye.png)

### fungsi rekursi
#### Fungsi rekursif didefinisikan oleh dua bagian:
##
(i)  Basis 
    -Bagian yang berisi nilai fungsi yang terdefinisi        secara eksplisit. 
    -Bagian ini juga sekaligus menghentikan rekursif        (dan memberikan sebuah nilai yang terdefinisi pada      fungsi rekursif).
    
(ii)  Rekurens
    -Bagian ini mendefinisikan fungsi dalam                  terminologi dirinya sendiri. 
    -Berisi kaidah untuk menemukan nilai fungsi pada        suatu input dari nilai-nilai lainnya pada input        yang lebih kecil. 

## 
Contoh 6:  Misalkan f didefinsikan secara rekusif sbb
![image](https://hackmd.io/_uploads/H1R_whlQkg.png)

![image](https://hackmd.io/_uploads/By2tv3xQye.png)
![image](https://hackmd.io/_uploads/ByscvhgXJx.png)

## 
Contoh 7: Nyatakan n! dalam definisi rekursif
![image](https://hackmd.io/_uploads/rJzaP3eX1g.png)
![image](https://hackmd.io/_uploads/r1pTvhxmyx.png)

![image](https://hackmd.io/_uploads/H15kdhgQkl.png)

## 
Contoh 8: Barisan Fibonacci  0, 1, 1, 2, 3, 5, 8, 11, 19, …. Dapat dinyatakan secara rekursif sebagai berikut:
![image](https://hackmd.io/_uploads/r1Fddhemkl.png)

## 
Contoh 9: Fungsi (polinom) Chebyshev dinyatakan sebagai
![image](https://hackmd.io/_uploads/BJLqd2eQkx.png)

## 
Contoh 10: Sumasi ![image](https://hackmd.io/_uploads/SJhhOheXJx.png)
didefinisikan secara rekursif sebagai  berikut
![image](https://hackmd.io/_uploads/BySRunlm1l.png)
sehingga ![image](https://hackmd.io/_uploads/BkWxYhxQke.png)


## struktur rekursi
-Struktur data yang penting dalam komputer adalah pohon biner (binary tree). 
![image](https://hackmd.io/_uploads/BJEOK3xm1l.png)
-Simpul (node) pada pohon biner mempunyai paling banyak  dua buah anak.

-Jumlah anak pada setiap simpul bisa 1, 2, atau 0.

-Simpul yang mempunyai anak disebut simpul cabang (branch node) atau simpul dalam (internal node)

-Simpul yang tidak mempunyai anak disebut simpul daun (leave).

-Pohon biner adalah struktur yang rekursif, sebab setiap simpul mempunyai cabang yang juga berupa pohon. Setiap cabang disebut  upapohon (subtree).
![image](https://hackmd.io/_uploads/HJv3Yne7kl.png)

-Oleh karena itu, pohon dapat didefinisikan secara rekursif sebagari berikut:

	(i) Basis: kosong adalah pohon biner
	(ii) Rekurens: Jika T1 dan T2 adalah pohon biner,            maka  adalah pohon biner

-Proses pembentukan pohon biner secara rekursif:
![image](https://hackmd.io/_uploads/BJBz93gmJg.png)

