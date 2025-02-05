# Merge-Sort
Merge Sort, böl ve fethet (divide and conquer) algoritmasında çalışır. Verilen dizi önce alt dizilere bölünür, sonra her bir alt dizi sıralanır ve birleşir.
**[16,21,11,8,12,22]-> Merge Sort

**Soru 1**
-Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
 **1.Adım** Bölme(Divide)
 Diziyi sürekli oalrak ikiye böleriz;
  [16, 21, 11, 8, 12, 22] → [16, 21, 11] ve [8, 12, 22]
  [16, 21, 11] → [16] ve [21, 11]
  [21, 11] → [21] ve [11]
  [8, 12, 22] → [8] ve [12, 22]
  [12, 22] → [12] ve [22]
 
 **2.Adım** Birleştirme(Merge)
 Bölünen dizileri sıralayıp birleştiririz;
  [21] ve [11] → [11, 21]
  [16] ve [11, 21] → [11, 16, 21]
  [12] ve [22] → [12, 22]
  [8] ve [12, 22] → [8, 12, 22]
  [11, 16, 21] ve [8, 12, 22] → [8, 11, 12, 16, 21, 22]
  
 **Sonuç** = [8, 11, 12, 16, 21, 22]

**Soru 2**
 -Big-O Gösterimi.
  Merge Sort algoritmasının Big-O zaman karmaşıklığı: O(n log n)
  n: Dizideki eleman sayısı log n: Her bölünmede yapılan işlem sayısı



                                                                                                                                
                                                                                                                                      
                                                                                                                                                    Sefa Emir Kalkan
