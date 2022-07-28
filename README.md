# Merge-Sort-Proje
https://app.patika.dev/zeyneepeergin

[16,21,11,8,12,22]

1.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

# ÇÖZÜM
Diziyi ikişer elemanı kalan parçalara inene kadar sürekli olarak ikiye böleriz. Sonra bu parçaları kendi içlerinde sıralayarak birleştiririz. Sonuçta elde edilen dizi sıralı dizinin kendisidir.

                                         [16,21,11,8,12,22]
           Level 0 
                              [16,21,11]                [8,12,22]
           Level 1
                          [16,21]      [11]        [8,12]        [22]
           Level 2
                           [16]    [21]    [11]       [8]    [12]   [22]
           Merge(Level 2)
                           [16,21]   [11]             [8,12]   [22]
           Merge(Level 1)
                              [11,16,21]                [8,12,22] 
           Merge(Level 0)
                                          [8,11,12,16,21,22]
																
2.Big-O gösterimini yazınız.		
	             
							 O(n*logn)
	
																
