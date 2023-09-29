Nama : Wisnu Ikhwansyah Saputra

Nim : 312210305

Kelas : TI 22.A3

---

<p align="center> Latihan Pemrograman Menggunakan Bahasa Python </p>

## Latihan 1

Sekarang kita akan mempelajari penggunaan "end, sep, dan string formatting"

untuk penggunaan "end" coba masukan perintah seperti di bawah ini : 

    print('Z', end=' ')
    print('Y', end=' ')
    print('X', end=' ')
    print('W', end=' ')

maka outputnya akan terlihat seperti ini

<img width="56" alt="Step 1" src="https://user-images.githubusercontent.com/110619093/198941900-896ce7a2-6879-4f72-a5e2-0d35c169bc48.png">

"end" berfungsi untuk mengganti karakter terakhir bawaan yang dicetak di layar. Jadi secara bawaan, setiap kali kita memanggil fungsi print() untuk mencetak sesuatu, python akan mencetak karakter ganti baris ( ) di setiap output.

untuk "sep" gunakan perintah seperti ini :

    a, b, c, d, = 1, 2, 3, 4, 
    print(a, b, c, d,)
    print(a, b, c, d, sep=',')
    print(a, b, c, d, sep=':')
    print(a, b, c, d,  sep='-')
    
maka outputnya akan terlihat seperti ini :

<img width="68" alt="Step 2" src="https://user-images.githubusercontent.com/110619093/198942370-a9cd8103-3d99-4ae9-83da-2e0c3fa6b415.png">

sep adalah pemisah(separator) yang berfungsi sebagai tanda pemisah antar objek yang dicetak.

dan untuk penggunaan string formatting coba masukan perintah berikut :

    print('{0:>3} {1:>16}'.format(0, 10**0))
    print('{0:>3} {1:>16}'.format(1, 10**1))
    print('{0:>3} {1:>16}'.format(2, 10**2))
    print('{0:>3} {1:>16}'.format(3, 10**3))
    print('{0:>3} {1:>16}'.format(4, 10**4))
    print('{0:>3} {1:>16}'.format(5, 10**5))
    
maka outputnya akan terlihat seperti ini : 

<img width="164" alt="Step 3" src="https://user-images.githubusercontent.com/110619093/198943275-45f68d4b-afe7-427b-84b5-c37ed677fa33.png">

String Formatting atau Pemformatan string memungkinkan kita menyuntikkan item ke dalam string.

---

## Latihan 2

kegunaan fungsi "input" pada python

masukan perintah seperti berikut :

    a=input("masukkan nilai a: ")
    b=input("masukkan nilai b: ")
    
print dengan string formatting menggunakan %s karena angka yang diinputkan terhitung variabel

    print("hasil penggabungan {1}&{0}=%s".format(a,b) %(a+b))
    
ubah menjadi integer

    a=int(a)
    b=int(b)
    
print kedua hasil dengan string formatting menggunakan %d

    print("hasil penjumlahan {1}+{0}=%d".format(a,b) %(a+b))
    print("hasil pembagian {1}/{0}=%d".format (a,b) %(a/b))
    
---
    
## Latihan 3

<img width="78" alt="Step 4" src="https://user-images.githubusercontent.com/110619093/198944593-fa59dc6e-ffdd-4109-a4b0-02ee68871543.png">

---

## Menentukan luas dan keliling lingkaran

Flowchart keliling dan luas lingkaran

![Flowchart Menghitung Luas dan Keliling Leingkaran](https://user-images.githubusercontent.com/110619093/198944837-08f98f13-4e11-4894-8d6a-022b03710b9d.png)

kode program keliling dan luas lingkaran

masukan π dan jari-jarinya

    pi = 3.14
    r = float(input("Masukkan Jari-Jari: "))
    
lalu masukan rumusnya

    luas = pi * r ** 2
    keliling = 2 * pi * r
    
cetak hasilnya menggunakan string formatting

    print("Luas Lingkaran =","{:.1f}".format(luas))
    print("Keliling Lingkaran =","{:.1f}".format(keliling))
    
maka outputnya akan terlihat seperti ini :

<img width="191" alt="Step 5" src="https://user-images.githubusercontent.com/110619093/198945867-cd8646ef-87aa-4f66-b6aa-426e2729bfe7.png">

---

Mungkin hanya itu saja yang bsa saya sampaikan kurang lebihnya mohon maaf:)
