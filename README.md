# Merge-Sort-Project
***1-)***[16,21,11,8,12,22] Dizisinin Merge Sorta göre aşamalarını yazınız.

[16,21,11]    -    [8,12,22]

[16] + [21,11]  -  [8] + [12,22]

[16] + [21]+[11] -  [8] + [12]+[22]

[16] + [11,21]  -  [8] + [12,22]

[11,16,21] + [8,12,22]

[8,11,12,16,21,22]

***2-)*** Big-O gösterimini yazınız.

Diziyi tek elemanlı olarak parçalayana kadar sürekli ikiye bölmektedir. Bölünmüş her dizide işlem için dizinin uzunluğu kadar olan n tane işlem yapıldığına göre = 
O(n*(logn)) => O(6*(log6)) olacak.
