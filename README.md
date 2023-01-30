# Praktikum-3
## Tugas Bahasa Pemograman pertemuan 6

Nama : Selma Ohoira

NIM : 312210727

Kelas : TI.22.C9

Prodi : Teknik Informatika

Langkah-langkahnya yaitu :
1. Install Pycharm di https://www.jetbrains.com/pycharm/download/#section=windows
2. Pilih yang community
![Gambar](gambar/1.png)
![Gambar](gambar/2.png)
![Gambar](gambar/3.png)
Tunggu hingga selesai, dan program siap digunakan.


### CARA MENJALANKAN PYCHARM
# Latihan 1
1. Klik new project
2. Ketik nama project sesuai yang diinginkan.
3. Pilih Previously Configurred interperter lalu klik yang add interperter dan pilih yang System interperter
4. Klik yang versi Python anda seperti gambar di bawah ini
![Gambar](gambar/4.png)
![Gambar](gambar/5.png)
5. Selanjutnya membuat file Phyton baru dan beri nama file
![Gambar](gambar/6.png)
6. Masukan code dari latihan 1 pada modul
7. Lalu run


## PENGGUNAAN END
print('A', end='') print('B', end='') print('C', end='') print() print('X') print('Y') print('Z')

## PENGGUNAAN SEPARATOR
w, x, y, z = 10, 15, 20, 25 print(w, x, y, z) print(w, x, y, z, sep=',') print(w, x, y, z, sep='') print(w, x, y, z, sep=':') print(w, x, y, z, sep='-----')

## STRING FORMAT
print(0, 10 ** 0) print(1, 10 ** 1) print(2, 10 ** 2) print(3, 10 ** 3) print(4, 10 ** 4) print(5, 10 ** 5) print(6, 10 ** 6) print(7, 10 ** 7) print(8, 10 ** 8) print(9, 10 ** 9) print(10, 10 ** 10)

## STRING FORMAT
print('{0:>3} {1:>16}'.format(0, 10 ** 0)) print('{0:>3} {1:>16}'.format(1, 10 ** 1)) print('{0:>3} {1:>16}'.format(2, 10 ** 2)) print('{0:>3} {1:>16}'.format(3, 10 ** 3)) print('{0:>3} {1:>16}'.format(4, 10 ** 4)) print('{0:>3} {1:>16}'.format(5, 10 ** 5)) print('{0:>3} {1:>16}'.format(6, 10 ** 6)) print('{0:>3} {1:>16}'.format(7, 10 ** 7)) print('{0:>3} {1:>16}'.format(8, 10 ** 8)) print('{0:>3} {1:>16}'.format(9, 10 ** 9)) print('{0:>3} {1:>16}'.format(10, 10 ** 10))

![Gambar](gambar/7.png)
![Gambar](gambar/8.png)

Hasil run

![Gambar](gambar/9.png)


# Latihan 2
1. Buat latihan baru "Latihan 2"
2. Masukan code program

![Gambar](gambar/10.png)

Hasil run

![Gambar](gambar/11.png)


# Latihan 3
1. Buat latihan baru "Latihan 3"

![Gambar](gambar/12.png)

2. Masukan code program
string = ""
x = int(input("Masukkan angka :")) bar = x

# Looping Baris
while bar >= 0:
# Looping Kolom Spasi Kosong
kol = bar while kol > 0: string = string + " " kol = kol - 1
# Looping Kolom Bintang Sisi Kiri
kiri = 1 while kiri < (x - (bar-1)): string = string + " * " kiri = kiri + 1
# Looping Kolom Bintang Sisi Kanan
kanan = 1 while kanan < kiri -1: string = string + " * " kanan = kanan + 1
string = string + "\n\n" bar = bar - 1
bar = 1
# Looping Baris
while bar <= x: kol = bar+1
# Looping Kolom Spasi Kosong
while kol > 1: string = string + " " kol = kol - 1
# Looping Kolom Bintang Sisi Kiri
kiri = 0 while kiri < (x - bar): string = string + " * " kiri = kiri + 1
# Looping Kolom Bintang Sisi Kanan
kanan = kiri while kanan > 1: string = string + " * " kanan = kanan - 1
string = string + "\n\n" bar = bar + 1 print (string)

![Gambar](gambar/13.png)
![Gambar](gambar/14.png)

Hasil Run

![Gambar](gambar/15.png)

## MENGHITUNG LUAS DAN KELILING LINGKARAN
1. Buat file baru "Praktikum3"
2. Masukan code program
print('menghitung luas dan keliling lingkarang') print('________________________________________')
r=float(input('masukkan nilai jari - jari :'))
phi=3.14 diameter=2*r
print('\nluasnya =', str("%.2f" % luas)) print('kelilingnya =', str("%.2f" % keliling))

![Gambar](gambar/16.png)

Hasil Run

![Gambar](gambar/17.png)

# Flowchart Menghitung luas dan keliling lingkaran

![Gambar](gambar/18.png)