# Merge-Sort-Project


Verilen dizi: [16, 21, 11, 8, 12, 22]

Merge Sort algoritması, listenin ortasını bulup ikiye ayırarak, bu alt listeleri tekrar aynı yöntemle parçalara ayırır ve bu işlem, listenin tek elemanlı alt listelere ayrılana kadar devam eder. Daha sonra alt listeler birleştirilirken sıralı hale getirilir. İşlemin sonunda listenin tamamı sıralanmış olur.

1.adım: [16, 21, 11], [8, 12, 22]
2.adım: [16], [21, 11], [8], [12, 22]
3.adım: [16], [11, 21], [8], [12, 22]
4.adım: [11, 16, 21], [8, 12, 22]
5.adım: [8, 11, 12, 16, 21, 22]
Dizi sıralı hale gelmiştir.

Big-O gösterimi: O(n*log(n))

Merge Sort'un ortalama, en iyi ve en kötü durumda karmaşıklık analizi O(n*log(n)) şeklindedir. 
