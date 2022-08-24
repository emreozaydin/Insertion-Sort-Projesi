# Veri Yapıları ve Algoritmalar > Insertion Sort Projesi

# Proje 1

## [22,27,16,2,18,6] -> Insertion Sort

### 1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
1. [22-16-27-2-18-6] 27 sayısı önce soldaki rakam ile kendini kıyaslar, ondan büyük olduğu için yerinde kalır. Sonra sağındaki 16 dan büyük olduğu için 16 ile yer değiştirir.

2. [16-22-27-2-18-6] 16 kendini soldaki 22 ile kıyaslar ve yer değiştirirler.

3. [16-22-2-27-18-6] bu aşamadan sonra 2 sayısı kendini sürekli soldaki sayılarla kıyaslamaya başlar ve önce 27 ile yer değiştirir.

4. [16-2-22-27-18-6] 2 sayısı 22 sayısı ile kendini kıyaslar ve yer değiştirir.

5. [2-16-22-27-18-6] 2 sayısı 16 sayısı ile kendini kıyaslar ve yer değiştirir.

6. [2-16-22-18-27-6] bu aşamadan sonra 18 sayısı kendini sürekli soldaki sayılarla kıyaslamaya başlar ve önce 27 ile yer değiştirir.

7. [2-16-18-22-27-6] 18 sayısı 22 sayısı ile kendini kıyaslar ve yer değiştirir. Kendisini 16 ile kıyaslayıp daha küçük olmadığı için yerinde kalır.

8. [2-16-18-22-6-27] bu aşamadan sonra 6 sayısı kendini sürekli soldaki sayılarla kıyaslamaya başlar ve önce 27 ile yer değiştirir.

9. [2-16-18-6-22-27] 6 sayısı 22 sayısı ile kendini kıyaslar ve yer değiştirir.

10. [2-16-6-18-22-27] 6 sayısı 18 sayısı ile kendini kıyaslar ve yer değiştirir.

11. [2-6-16-18-22-27] 6 sayısı 16 sayısı ile kendini kıyaslar ve yer değiştirir. Kendisini 2 ile kıyaslayıp daha küçük olmadığı için yerinde kalır.

### 2. Big-O gösterimini yazınız.

O(n^2)

### 3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

### 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Yukarıdaki açıklamaya göre 18 sayısı dizinin ortasında bulunduğu için Avarage Case kapsamına girer.
