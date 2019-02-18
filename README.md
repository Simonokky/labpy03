# Praktikum 3
# Step by step algoritma progam latihan1.py, latihan2.py, dan program1.py
# Algoritma latihan1.py
# Step 1 Algoritma latihan1.py
Sebelum memulai membuatnya, silahkan buka aplikasi Sublime terlebih dahulu, karna disini saya menggunakan Sublime.
![1](https://user-images.githubusercontent.com/46946915/52936819-fa0ce600-338f-11e9-9507-c0d4b2258e78.png)
# Step 2 Algoritma latihan1.py
line 1 silahkan ketik "print ('Masukkan nilai N: 5')"
![2](https://user-images.githubusercontent.com/46946915/52937064-ad75da80-3390-11e9-8721-4429179c7fb5.png)
Dan Line 2 sampai Line 9, ketik seperti ini :
```
import random
jumlah = 5
a = 0
for x in range(jumlah):
	i = random.uniform(.0,.5)
	a+=1
	print('data ke:',a,'==>', i)
print ('selesai')

"print"  : berfungsi untuk mencetak atau menampilkan objek ke perangkat keluaran (layar) atau ke file teks.
"import" : fungsi lanjut yang dipanggil oleh statement import.
"random" : untuk menentukan suatu pilihan. 
"range"  : merupakan fungsi yang menghasilkan list. Fungsi ini akan menciptakan sebuah list baru dengan rentang nilai tertentu. 
"uniform": digunakan untuk menampilkan bilangan float random dengan batas awal bilangan x, dan batas akhir bilangan y.
```
![3](https://user-images.githubusercontent.com/46946915/52937348-7d7b0700-3391-11e9-85f7-7c8c4fbd21bb.png)
# Step 3 Algoritma latihan1.py
Jika sudah, dan sama seperti apa yang ada di "Step 2" silahkan save program kalian. Dan jalankan program tersebut melalui command prompt.

Dan jika program yang tadi kita buat berhasil, maka tampilannya seperti dibawah ini:
![4](https://user-images.githubusercontent.com/46946915/52937761-989a4680-3392-11e9-82b0-e9776bf9c93f.png)

# Algoritma latihan2.py
# Step 1 Algoritma latihan2.py
Sebelum memulai membuatnya, silahkan buka aplikasi Sublime terlebih dahulu, karna disini saya menggunakan Sublime.
![1](https://user-images.githubusercontent.com/46946915/52938260-d186eb00-3393-11e9-821a-4c1a275601a0.png)
# Step 2 Algoritma latihan2.py
line 1 sampai line 8, ketik seperti ini :
```
max=0
while True:
	a=int(input('Masukkan bilangan='))
	if max < a:
		max = a
	if a==0:
		break
print('Bilangan terbesarnya adalah',max)

"max"	: fungsi bulid-in untuk mencari nilai tertinggi. Fungsi ini dapat diberikan sebuah parameter berupa angka.
"while"	: disebut uncounted loop (perulangan yang tak terhitung), untuk perulangan yang memiliki syarat dan tidak tentu berapa banyak perulangannya.
"int"	: berfungsi mengkonversi bilangan maupun string angka menjadi bilangan bulat (integer).
"if"	= Bila suatu kondisi tertentu tercapai maka apa yang harus dilakukan. Dengan fungsi ini kita bisa menjalankan suatu perintah dalam kondisi tertentu. 
"input"	: masukan yang kita berikan ke program.
"break"	: fungsi yang menghentikan operasi dibawahnya jika suatu kondisi yang ditentukan telah tercapai.
"print"	: berfungsi untuk mencetak atau menampilkan objek ke perangkat keluaran (layar) atau ke file teks.
```
![2](https://user-images.githubusercontent.com/46946915/52938426-3b9f9000-3394-11e9-9bc3-77e626e0a636.png)
# Step 3 Algoritma latihan2.py
Jika sudah, dan sama seperti apa yang ada di "Step 2" silahkan save program kalian. Dan jalankan program tersebut melalui command prompt.

Dan jika program yang tadi kita buat berhasil, maka tampilannya seperti dibawah ini:
![3](https://user-images.githubusercontent.com/46946915/52939034-bd43ed80-3395-11e9-863f-0e72ccb99ec7.png)

# Algoritma program1.py
# Step 1 Algoritma program1.py
Sebelum memulai membuatnya, silahkan buka aplikasi Sublime terlebih dahulu, karna disini saya menggunakan Sublime.
![0](https://user-images.githubusercontent.com/46946915/52939453-cf725b80-3396-11e9-82e6-a265f7e410f0.png)
# Step 2 Algoritma program1.py
line 1 sampai line 16, ketik seperti ini :
```
a = 100000000
for x in range(1,9):
	if(x>=1 and x<=2):
		b=a*0
		print('Laba bulan ke-',x,' :',b)
	if(x>=3 and x<=4):
		c=a*0.1
		print('Laba bulan ke-',x,' :',c)
	if(x>=5 and x<=7):
		d=a*0.5
		print('Laba bulan ke-',x,' :',d)
	if(x==8):
		e=a*0.2
		print('Laba bulan ke-',x,' :',e)
total = b+b+c+c+d+d+d+e
print('\nTotal : ', total)

"print"	= Fungsi "print()" berfungsi untuk mencetak atau menampilkan objek ke perangkat keluaran (Layar).
"if"	= Bila suatu kondisi tertentu tercapai maka apa yang harus dilakukan. Dengan fungsi ini kita bisa menjalankan suatu perintah dalam kondisi tertentu. 
"for"	= Perulangan yang terhitung.
"range" = Mengembalikan deret integer berurut pada range yang ditentukan dari start sampai stop.
"for x in range" = "for" perulangan yang terhitung, dan "range" mengembalikan deret integer berurut pada range yang ditentukan dari start sampai stop.
"\nTotal" = Membuat garis baru, dan menampilkan total hasil dari apa yang kita inginkan.
```
ingat perhatikan setiap penggunaan titik dan koma!
![2](https://user-images.githubusercontent.com/46946915/52939922-e49bba00-3397-11e9-8992-ef7fad951a4d.png)
# Step 3 algoritma program1.py
Jika sudah, dan sama seperti apa yang ada di "Step 2" silahkan save program kalian. Dan jalankan program tersebut melalui command prompt.

Dan jika program yang tadi kita buat berhasil, maka tampilannya seperti dibawah ini:
![3](https://user-images.githubusercontent.com/46946915/52940496-4b6da300-3399-11e9-88d6-001c46c961c5.png)

        Sekian Dan Terimakasih ,Simon Okky I.W 18.TI.A1



