# PertemuanKe7

NAMA: ALFHIN CHORRYAGNESHA AZIZ <br>
KELAS: TI. 20. A.1 <br>
NIM: 312010504 <br>

Jadi pada pertemuan ini saya diberikan beberapa tugas oleh dosen saya yaitu diantaranya:

![poto1](https://user-images.githubusercontent.com/73273061/98397809-7e3a5c00-2092-11eb-8a00-c5e69891fb90.png) <br>

Pada tugas pertama, saya diminta untuk membuat sebuah program pengulangan bertingkat yang nantinya akan menghasilkan output seperti gambat diatas. Untuk bisa dapat menghasilkan output tersebut maka saya memasukan syntax:

    baris = 10
    kolom = baris

    for bar in range(baris):
    for col in range(kolom):
        tab = bar+col
        print("{0:>5}".format(tab), end='')
    print()
    
Mengapa demikian? Karena untuk dapat melakukan pengulangan bertingkat kamu perlu memasukan

    for bar in range(baris):
    for col in range(kolom):
        tab = bar+col
        print("{0:>5}".format(tab), end='')
    print()
    
dan karena pada syntax tersebut kamu membutuhkan baris dan kolom maka sebelum memasukan syntax diatas kamu perlu menambahkan keterangan baris dan kolom sesuai yang kalian butuhkan seperti ini.

    baris = 10
    kolom = baris
Jika sudah memasukan semua syntax diatas dan telah di run, maka kamu akan mendapatkan tampilan seperti gambar yang ada dibawah ini
![foto2](https://user-images.githubusercontent.com/73273061/98401248-f2c3c980-2097-11eb-8bad-f9ace4f8fe73.png)
