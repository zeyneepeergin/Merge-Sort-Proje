# Merge-Sort-Proje
[16,21,11,8,12,22]

1.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

# ÇÖZÜM
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
	
																
