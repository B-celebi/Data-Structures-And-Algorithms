[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

16,21,11     8,12,22   2^x = n

16,21 11     8 12,22   2^x = n

11,16,21     8,12,22   2^x = n

8,11,12,16,21,22

n kere 2^x = n => Big-O-Notation = O(nlogn)