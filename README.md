# Veri Yapilari Ve Algoritmalar
Patika.dev - Veri Yapıları ve Algoritmaları dersi bitirme projesi
# Insertion Sort Projesi
[22,27,16,2,18,6] -> Insertion Sort

```
- 1 - Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

- 2 - Big-O gösterimini yazınız.

- 3 - Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

- 4 - Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

- 5 - [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```

## 1 - Insertion Sort Asamalari
```
[22|,27,16,2,18,6]
[22,27|,16,2,18,6]
[16,22,27|,2,18,6]
[2,16,22,27|,18,6]
[2,16,18,22,27|,6]
[2,6,16,18,22,27]
```

## 2 - Big O Notation Gösterimi
Worst Case: n + (n-1) + (n-2) + ..... + 1 = (n.(n+1))/2 = n^2/2 + n/2 --> O(n^2)

## 3 - Time Complexity
```
Best Case : [2,6,16,18,22,27]
Worst Case : [27,22,18,16,6,2]
```
## 4 - 18 Sayısı Case Durumu
Son Hali --> [2,6,16,18,22,27], 18 sayısı ortadadır bu yüzden "Average case" diyebiliriz.

## 5 - [7,3,5,8,2,9,4,15,6] dizisi ilk 4 adım
```
[7|3,5,8,2,9,4,15,6]
[3,7|5,8,2,9,4,15,6]
[3,5,7|8,2,9,4,15,6]
[3,5,7,8|2,9,4,15,6]
```
www.patika.dev
