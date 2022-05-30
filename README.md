# Insertion Sort Project

## www.patika.dev Insertion sort projesi

### Proje 1

---

[22,27,16,2,18,6] -> Insertion Sort

## 1. Problem

* 1. aşama [*2*,27,16,*22*,18,6] n işlemde en küçük sayı arandı ve en başa geçirildi. (22-2)
* 2. aşama [2,*6*,16,22,18,*27*] n-1 işlemde en küçük sayı arandı ve yer değiştirildi. (27-6)
* 3. aşama [2,6,*16*,22,18,27] n-2 işlemde 16 sayısının en küçük sayı olduğu görüldü değiştirilme yapılmadı.
* 4. aşama [2,6,16,*18*,*22*,27] n-3 işlemde 18-22 yer değiştirildi.
* 5. aşama [2,6,16,18,*22*,*27*] n-4 işlemde 22 -27 halihazırda sıralanmış olarak görüldü değişiklik yapılmadı.
* 6. aşama [2,6,16,18,22,27] 1 insertion sort işlemi tamamlandı.

---

## 2. Problem

n+ (n-1) + (n-2) + (n-3) + (n-4) + 1 = x 
(n*(n+1))/2 => (n^2 + n)/2
n^2 baskınlığı ile Big-O gösterimi = O(n^2)

## 3. Problem

Average Case : O(n^2)
Worst Case: O(n^2)
Best Case : O(n)

## 4. Problem
18 sayısı dizinin orta bölümünde konumlandığı için "**Avarage case**" kapsamına girer

---

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı

* [**2**,3,5,8,**7**,9,4,15,6]
* [2,3,5,8,7,9,4,15,6]
* [2,3,**4**,8,7,9,**5**,15,6]
* [2,3,4,**5**,7,9,**8**,15,6]

