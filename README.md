## latihan 1

mula-mula kita buat input terlebih dahulu contohnya seperti dibawah ini:

a = int(input('masukan bilangan pertama : '))

b = int(input('masukan bilangan kedua : '))

lalu kita enter, masukan if untuk menjalani program yang sebelumnya dan tambahkan x > y : lalu print('Bilangan terbesar = ', x)

lalu tambahkan else untuk menambah aksi untuk menentukan bahwa x lebih besar dari y 

 else :
 
      print('Bilangan terbesar = ', y)
      
dan saat running kita diminta untuk memasukan bilangan pertama lalu bilangan kedua,      
lalu hasil runing nya seperti gambar berikut:

![gambar](gambarlab4/rid1.png)

## latihan 2

mula-mula kita buat input terlebih dahulu contohnya seperti dibawah ini:

a = int(input('bilangan ke-1 = '))

b = int(input('bilangan ke-2 = '))

c = int(input('bilangan ke-3 = '))

lalu tambahkan 

if a < b:

    if b < c:
    
        print('urutan bilangan : ', a, b, c)
        
    else:
    
        print('urutan bilangan : ', c, a, b)
        
else:

    if a < c:
    
        print('urutan bilangan : ', b, a, c)
        
    else:
    
        if b < c:
        
            print('urutan bilangan : ', b, c, a)
            
         else:
         
            print('urutan bilangan : ', c
            
dan saat runing kita sebut bilangan yang inin kita ururkan 
lalu hasil runing nya seperti gambar berikut:

![gambar](gambarlab4/rid2.png)

## latihan 3

mula-mula kita buat koddinagnnya dulu seperti berikut:

for i in range(0, 10):

    for j in range(0, 10):
    
        product = i+j
        
        print(f"{product:>3}", end='')
    print()

x = input("masukan angka :")

if x > y:

    print(x, "y")
    
print("ini diluar pernyataan if")

maka runingannya akan seperti gambar berikut:

![gambar](gambarlab4/rid3.png)

## latihan 4

mula-mula kita buat koddinagnnya dulu seperti berikut:

import random

n = int(input("masukan nilai N : "))

for i in range(n):

    a = random.uniform(0.0, 0.5)
    
    print("data ke :", i+1, "=> ", a)
    
    print('sahrul ridwamsyah')
    
setelah runing akan diminta masukan nilai n, disini saya memasukan nilai n-nya 12
dan hasil runningannya akan seperti gambar berikut:

![gambar](gambarlab4/rid4.png)








 



