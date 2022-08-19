Binary Search Tree Projesi
# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]
dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

---

|  |  |  |  |  |  |  |  |  |  |  |  |  | 
|--|--|--|--|--|--|--|--|--|--|--|--|--|
|  |  |  |  |  |  |  | 5|  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  |  |  |/ |  |  |  |\ |  |  |  |
|  |  |  |  |1 |  |  |  |  |  |8 |  |  |
|  |  |  | /|  |\ |  |  |  | /|  |\ |  |
|  |  | 0|  |  |  |3 |  | 6|  |  |  |9 |
|  |  |  |  |  | /|  |\ |  |\ |  |  |  |
|  |  |  |  |2 |  |  |  | 4|  |7 |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  | 
|  |  |  |  |  |  |  |  |  |  |  |  |  |

 ROOT:5  
--- 
>1.Eklenecek sayı = 8  
8>5 olduğu için  5'in  sağına ekliyoruz.

>2.Eklenecek sayı = 6  
6>5 ve 6<8 olduğu için 8'in soluna ekliyoruz.  

>3.Eklenecek sayı = 1  
1<5 olduğu için  5'in  soluna ekliyoruz.  

>4.Eklenecek sayı = 9  
9>5 ve 9>8 olduğu için  8'in  sağına ekliyoruz.

>5.Eklenecek sayı = 3  
3<5 ve 3>1 olduğu için  1'in  sağına ekliyoruz.

>6.Eklenecek sayı = 2  
2<5 ve 2>1 ve 2<3 olduğu için 3'ün soluna ekliyoruz.

>7.Eklenecek sayı = 7  
7>5 ve 7<8 ve 7>6 olduğu için  7'nin  sağına ekliyoruz.

>8.Eklenecek sayı = 4  
4<5 ve 4>1 ve 4>3 olduğu için 3'ün sağına ekliyoruz.

>9.Eklenecek sayı = 0  
0<5 ve 0<1 olduğu için  1'in  soluna ekliyoruz.  

# [Patika.dev](www.patika.dev)
