title: Tuhan dan Batu
date: 2014-08-08 20:48:56
keyword: Tuhan, Logika
category: Unek
tags:
    - Logika
    - Tuhan
    - Kebenaran
---
Beberapa bulan yang lalu gue diskusi dengan salah satu teman gue. Di tengah-tengah diskusi tersebut gue menyanyakan sebuah pertanyaan yang konon katanya pernah ditanyakan oleh seorang atheis.<!--more--> Pertanyaannya: 

  > **Apakah Tuhan dapat membuat batu yang sangat besar bahkan tuhan pun tidak dapat mengangkatnya?**

Sekilas, pertannyaan tersebut seperti pertanyaan jebakan. Bahkan teman diskusi gue bilang pertanyaan tersebut tidak dapat dijawab. Alasannya, jika dia menjawab **ya**, seolah dia berkata bahwa tuhan tidak dapat mengangkat sebuah batu, padahal tuhan maha perkasa. Dan jika dia menjawab **tidak**, seolah dia berkata bahwa tuhan tidak dapat mencipta sebuah batu, padahal tuhan maha pencipta. Oleh karenanya temen gue main aman dengan berkata bahwa pertanyaan tersebut tidak boleh dijawab. Tapi, meskipun dia perempuan, bukan berarti gue harus selalu mengalah.

Mari kita jawab pertanyaan tersebut dengan pendekatan [FOL](http://en.wikipedia.org/wiki/First-order_logic). Pertama, kita definisikan semua term yang akan dipakai.

  > Dapat(S, P, O) = S dapat melakukan P terhadap objek O
  > BatuBesar(X) = X adalah batu yang sangat besar
    
Selanjutnya kita buat sebuah pernyataan **p**: *Tuhan dapat membuat sebuah batu yang sangat besar dan tuhan tidak dapat mengangkat batu tersebut*. Kemudian kita ubah **p** menjadi FOL.
  > **p** : BatuBesar(x) && Dapat(Tuhan, Membuat, x) && !Dapat(Tuhan, Mengangkat, x)
  
Asumsikan Tuhan disini adalah Tuhan yang telah didefinisikan dalam Islam, yaitu tuhan yang maha segalanya.
Maka untuk setiap x: 
  > Dapat(Tuhan, Membuat, x) selalu bernilai BENAR; begitu juga
  > Dapat(Tuhan, Mengangkat, x) selalu bernilai BENAR.
  
Dengan demikian, **!Dapat(Tuhan, Mengangkat, x)** akan selalu bernilai SALAH, sehingga pernyataan **p** juga akan selalu bernilai **SALAH**. Meskipun **p** bernilai SALAH, bukan berarti *Tuhan* tidak dapat *Membuat x*. Secara keseluruhan kalimat **p** bernilai SALAH, tapi belum tentu semua anak kalimatnya bernilai SALAH.

Hari sudah sore, kami tetep *keukeuh* dengan jawaban masing-masing. Teman diskusi gue bilang akan mendiskusikan pertanyaan tersebut dengan kakaknya. Keesokan harinya gue bertemu dia dan menanyakan hasil diskusinya dengan kakaknya. Aneh, tiba-tiba dia setuju dengan penjelasan gue. *Best case*-nya adalah, dia suka sama gue; *good case*-nya dia emang setuju dengan penjelasan gue; dan *worst case*-nya adalah kakaknya bilang <q>ga perlu tanggepin orang liberal</q>.

Innallaha a'lam. Gue hanya mencoba memanfaatkan ilmu yang diberikanNya untuk mencari solusi dari sebuah problema.